<html>
  <head>
    <title>SFDC MIAW - PRE Chat</title>
    <script type='text/javascript'>
      function initEmbeddedMessaging() {
        try {
          embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
    
          embeddedservice_bootstrap.init(
            '00D0o0000016oQo',
            'Github_Pre_Chat',
            'https://devhubdk-dev-ed.my.site.com/ESWGithubPreChat1717823863245',
            {
              scrt2URL: 'https://devhubdk-dev-ed.my.salesforce-scrt.com'
            }
          );
        } catch (err) {
          console.error('Error loading Embedded Messaging: ', err);
        }
      };
    </script>
    <script type='text/javascript' src='https://devhubdk-dev-ed.my.site.com/ESWGithubPreChat1717823863245/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </head>
  <body>
    <b>Hello</b>
    Start messaging with Pre-Chat
  </body>
</html>
