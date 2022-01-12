## Web Application API

1. Open  <a href="https://www.dynatrace.com/support/help/dynatrace-api/configuration-api/rum/web-application-configuration-api/web-application/post-web-application" target="_blank">Web app API</a> documentation

2. Go back to terminal and run dt api kit:

    ```javascript
    node index.js
    ```

3. Choose *Create new Web App*

4. ```
   Enter the name of your app: Sockshop (Production)
   Choose RUM enabled: yes/no
   Choose RUM % captured: 0-100
   Choose session replay enabled: yes/no
   Choose % of session replay capture: 0-100

    ```

5. Go to history.log and verify your deployment
    ![webapp](../../assets/images/webapp.png)
