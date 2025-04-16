Lab: Broken Access Control via Manipulação de Cookies
Descrição:

Esse laboratório demonstrou uma falha de controle de acesso onde o privilégio de usuário era determinado por um cookie armazenado no navegador. Ao interceptar e modificar esse cookie, foi possível assumir privilégios de administrador.

Técnica utilizada:

Interceptação de requisições HTTP com o Burp Suite

Identificação do cookie de sessão contendo uma flag role=admin ou similar

Modificação manual do valor do cookie para obter privilégios administrativos

Acesso a funcionalidade restrita: exclusão de usuário

Lição aprendida:

Cookies são dados do lado cliente e nunca devem ser usados como fonte confiável para controle de acesso. Qualquer dado que determina permissões deve ser validado no servidor e protegido contra manipulação.

Categoria OWASP:
🔐 Broken Access Control (1º lugar no Top 10 da OWASP 2021)
