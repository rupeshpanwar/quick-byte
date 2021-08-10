# App overview
**https://github.com/rupeshpanwar/React-Nodejs-fullstack.git**
<img width="276" alt="image" src="https://user-images.githubusercontent.com/75510135/128623787-8d718a5b-d500-44c4-9435-29f14f9e0383.png">


<img width="477" alt="image" src="https://user-images.githubusercontent.com/75510135/128623864-2688d4a7-da1b-45f8-a766-308373d511c6.png">

## tools n order
<img width="435" alt="image" src="https://user-images.githubusercontent.com/75510135/128624012-ef3614bb-658d-42c0-9d34-e3c5a8b2cd96.png">

# mockup
<img width="496" alt="image" src="https://user-images.githubusercontent.com/75510135/128624170-82b7f5ef-7f64-4618-b802-45a1a5507d3a.png">

<img width="636" alt="image" src="https://user-images.githubusercontent.com/75510135/128624211-4716dfd0-3c73-436c-8fac-0eec2489da6e.png">

<img width="553" alt="image" src="https://user-images.githubusercontent.com/75510135/128624244-80e19101-6804-430a-9b3a-bbe736fd6014.png">

<img width="812" alt="image" src="https://user-images.githubusercontent.com/75510135/128624254-543b4f21-73e5-4e82-a2f3-980f999a2b0b.png">

<img width="520" alt="image" src="https://user-images.githubusercontent.com/75510135/128624519-38e58ab3-f5c7-458e-a293-46c8cb666ccf.png">

# App architecture and basic React app flow
<img width="364" alt="image" src="https://user-images.githubusercontent.com/75510135/128624672-ccb874cd-2e74-42f4-9f14-19522a7f008f.png">

# Express / node side API [Server]
        cd Full-Stack-App/
        mkdir server
        cd server
        npm init -y
        history
<img width="540" alt="image" src="https://user-images.githubusercontent.com/75510135/128624796-0f49a866-1add-4c1c-a00f-a75f03a39162.png">

* server $ npm i --save express

**? why node n express**
<img width="483" alt="image" src="https://user-images.githubusercontent.com/75510135/128625007-57fecbfc-76c8-4fdd-a7e5-e94aeb6332d9.png">

**Behind the scene**
<img width="536" alt="image" src="https://user-images.githubusercontent.com/75510135/128625068-e8b333cd-4070-4691-8a9a-652bffcdf5ea.png">

## route basics
<img width="736" alt="image" src="https://user-images.githubusercontent.com/75510135/128630231-dd04df72-79b6-4107-a713-a3f45a1c0b6a.png">
<img width="419" alt="image" src="https://user-images.githubusercontent.com/75510135/128630273-627ee38e-7d0c-4eee-8fda-78069a0b08fc.png">




- Generating express app
- test by running > node index.js
## Deploy to Heroku checklist
<img width="479" alt="image" src="https://user-images.githubusercontent.com/75510135/128632720-0a6f104d-aea8-4955-a183-0d61d42fdd66.png">
- spcify node env
<img width="584" alt="image" src="https://user-images.githubusercontent.com/75510135/128633019-d461d9f2-b87b-44a4-9986-9e68e5cae4cb.png">
- specify start script
<img width="559" alt="image" src="https://user-images.githubusercontent.com/75510135/128633087-ad0baa40-7adb-48d3-8ca4-20242a8152a9.png">
- .gitignore
<img width="518" alt="image" src="https://user-images.githubusercontent.com/75510135/128633153-234758d6-29cf-4b8c-99d1-c824b2e21e77.png">

## Heroku CLI deployment
<img width="551" alt="image" src="https://user-images.githubusercontent.com/75510135/128633238-4e5a7092-4538-4100-b648-038a70dcefa9.png">
- Create Heroku account
<img width="1025" alt="image" src="https://user-images.githubusercontent.com/75510135/128633503-c592ad75-0851-4145-a7d0-b2821e2beb47.png">
- commit the code to github
```
                                - install the git first
                                git init
                                git add .
                                git commit -m 'basic setup'
                        - install Heroku CLI and create App
                        - > brew install heroku
                        - > heroku -v
                        - Deploy App with Git
                        - > heroku login
                        - >  $ heroku create
 ```
Creating app... done, ⬢ frozen-scrubland-28418
https://frozen-scrubland-28418.herokuapp.com/ | https://git.heroku.com/frozen-scrubland-28418.git
- git remote add heroku https://git.heroku.com/frozen-scrubland-28418.git
-  Heroku Deploys project
```
                                    git init
                                    heroku git:remote -a frozen-scrubland-28418
                                    git add .
                                    git commit -am 'make it better'
                                    git push heroku master
                                    heroku open
                                    heroku logs
  ```
https://thawing-fortress-96360.herokuapp.com/ 
https://git.heroku.com/thawing-fortress-96360.git

# intro to google auth
<img width="511" alt="image" src="https://user-images.githubusercontent.com/75510135/128638928-776b18d4-67d0-4a34-986b-4943b2b1a88e.png">

<img width="514" alt="image" src="https://user-images.githubusercontent.com/75510135/128638990-e31dcb36-3585-4700-9381-3a7c76dcee0c.png">

<img width="495" alt="image" src="https://user-images.githubusercontent.com/75510135/128639032-00ce4c56-dea5-48ab-a1dc-4af5222b53d7.png">

<img width="726" alt="image" src="https://user-images.githubusercontent.com/75510135/128639076-83fdbf9a-0b90-4225-a4be-353605df5765.png">

<img width="770" alt="image" src="https://user-images.githubusercontent.com/75510135/128639191-f98455f8-0dc5-46b8-94fc-581900eeb7d5.png">
<img width="511" alt="image" src="https://user-images.githubusercontent.com/75510135/128639212-b4de5fe3-0785-4796-89a3-74d574699dc5.png">

# passport js
<img width="714" alt="image" src="https://user-images.githubusercontent.com/75510135/128639278-814c6ec7-655a-4cb2-a27d-af62384f66d6.png">

<img width="445" alt="image" src="https://user-images.githubusercontent.com/75510135/128639336-080313a4-f79a-4048-bcb6-023f8c969495.png">

* <img width="275" alt="image" src="https://user-images.githubusercontent.com/75510135/128649486-1e9477c9-0c08-4e6a-bdf3-50ca97466ba9.png">

# passport setup
* $ npm i --save passport passport-google-oauth20
<img width="528" alt="image" src="https://user-images.githubusercontent.com/75510135/128650706-fbf8e6c1-a178-4532-8eff-9621e4a566a6.png">

* create client id 
* login into https://console.cloud.google.com
<img width="909" alt="image" src="https://user-images.githubusercontent.com/75510135/128651264-c57ee31e-a1b2-4b39-8255-a8d387836815.png">
<img width="565" alt="image" src="https://user-images.githubusercontent.com/75510135/128651286-a6ed76bb-7c66-4649-b7fb-cf72efa43e4f.png">
<img width="981" alt="image" src="https://user-images.githubusercontent.com/75510135/128651310-4d6aca7f-bb84-4c9c-a45a-2ac118e0f0ad.png">
<img width="801" alt="image" src="https://user-images.githubusercontent.com/75510135/128651336-1137d513-9308-4f05-8db6-b503d16439cc.png">
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/75510135/128651370-1fad2f9d-3a3a-4743-ba37-c23e75a83b05.png">

<img width="1127" alt="image" src="https://user-images.githubusercontent.com/75510135/128651464-c1cd5df0-e773-40b3-86c2-a7b449429556.png">
<img width="1132" alt="image" src="https://user-images.githubusercontent.com/75510135/128651479-fcc5971a-f0a6-4642-b75c-be748636ebea.png">
<img width="880" alt="image" src="https://user-images.githubusercontent.com/75510135/128651593-299b4f03-8814-4fe1-a9ef-0a29d884ae98.png">
<img width="788" alt="image" src="https://user-images.githubusercontent.com/75510135/128651649-9d327b0b-bb20-497c-93bb-fbcbd5e5a0d1.png">
<img width="1128" alt="image" src="https://user-images.githubusercontent.com/75510135/128651690-d8230179-74a1-4a07-8ae4-5403cd98058e.png">

## Client ID
<img width="472" alt="image" src="https://user-images.githubusercontent.com/75510135/128656982-7e6dc678-5b65-44e7-a5b8-ad450bca6482.png">
<img width="388" alt="image" src="https://user-images.githubusercontent.com/75510135/128657476-ce34aabb-c5cd-4699-b794-f330651d3df1.png">
<img width="417" alt="image" src="https://user-images.githubusercontent.com/75510135/128657516-48955e43-8e82-49ba-b6ce-e7f134109770.png">

## BHS(behind the scene
<img width="590" alt="image" src="https://user-images.githubusercontent.com/75510135/128657153-c5f9f1eb-9795-4e8a-902e-338414e68544.png">


### consume google cliend ID now
<img width="587" alt="image" src="https://user-images.githubusercontent.com/75510135/128659311-96c59b74-df94-41dc-92f9-8cffdc17b8b9.png">

**https://github.com/rupeshpanwar/React-Nodejs-fullstack.git**

* Test by http://localhost:5000/auth/google

<img width="666" alt="image" src="https://user-images.githubusercontent.com/75510135/128660232-40282a93-dc56-4efc-8865-fce8d228c9a6.png">
<img width="1041" alt="image" src="https://user-images.githubusercontent.com/75510135/128662726-5b9d843d-c75c-4aaf-b0ef-e7858e5f30fa.png">

                                https://accounts.google.com/o/oauth2/v2/auth/oauthchooseaccount?response_type=code&
                                redirect_uri=http%3A%2F%2Flocalhost%3A5000%2Fauth%2Fgoogle%2Fcallback&
                                scope=profile%20email&client_id=85941131422-c7vm8p4f4q94edn7qpahdhutj3m5eaq5.apps.googleusercontent.com&
                                flowName=GeneralOAuthFlow
                               
                               
## complete the loop back for google oauth
<img width="830" alt="image" src="https://user-images.githubusercontent.com/75510135/128664007-b55e0308-ef3f-4b17-ba1c-373833f3d24a.png">

<img width="730" alt="image" src="https://user-images.githubusercontent.com/75510135/128664000-34feac3c-4277-4c10-b148-e6330df761b5.png">

## extract user profile information to submit to DB
<img width="830" alt="image" src="https://user-images.githubusercontent.com/75510135/128665323-3331353a-cbaa-40be-bff5-521a78103ded.png">

#####################################################################
## Nodemon setup
* npm i --save nodemon
* npm run dev
<img width="512" alt="image" src="https://user-images.githubusercontent.com/75510135/128665857-3fd087ec-129d-467f-8801-7ee0910a191b.png">


#####################################################################
## Server structure refactor
<img width="466" alt="image" src="https://user-images.githubusercontent.com/75510135/128666105-2d63ff77-ad15-42c2-9aca-94e63dccae20.png">
<img width="867" alt="image" src="https://user-images.githubusercontent.com/75510135/128676053-95bcf9c5-e440-4278-a71a-7d22ed6ef367.png">
#####################################################################
## Authentication mechanism
<img width="503" alt="image" src="https://user-images.githubusercontent.com/75510135/128679064-da5f0f6f-7b45-462a-b50d-8b7ef540b2f1.png">

<img width="612" alt="image" src="https://user-images.githubusercontent.com/75510135/128677467-0f29e744-05df-4d4c-a71d-9e6aeec5311d.png">

<img width="640" alt="image" src="https://user-images.githubusercontent.com/75510135/128677663-9d88b6d3-6c90-4582-b52a-26fce179e002.png">

* cookie based authentication

<img width="616" alt="image" src="https://user-images.githubusercontent.com/75510135/128678246-18a180e6-52e9-4a8b-aa8b-5960cc8b887f.png">

### Sign in User with oauth

<img width="598" alt="image" src="https://user-images.githubusercontent.com/75510135/128687108-8013fc06-6024-4219-8fca-1ab6ce1e28f9.png">

<img width="346" alt="image" src="https://user-images.githubusercontent.com/75510135/128687170-b71965c8-65af-4446-99a0-1d7165bf097f.png">

<img width="316" alt="image" src="https://user-images.githubusercontent.com/75510135/128688290-c3caf425-1c98-47ba-8fd3-6f432c0ef020.png">

<img width="830" alt="image" src="https://user-images.githubusercontent.com/75510135/128690082-5e892b09-df88-4160-b2d1-33128322a723.png">







