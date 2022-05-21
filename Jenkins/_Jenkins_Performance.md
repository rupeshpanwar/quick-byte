- https://support.cloudbees.com/hc/en-us/articles/222446987-Prepare-Jenkins-for-Support
- https://www.cloudbees.com/blog/enterprise-jvm-administration-and-jenkins-performance
- https://docs.cloudbees.com/docs/admin-resources/latest/jvm-troubleshooting/
- https://support.cloudbees.com/hc/en-us/articles/230922208-Pipeline-Best-Practices
- https://wiki.jenkins.io/display/JENKINS/Active+Directory+plugin
- https://go.cloudbees.com - CloudBees Support Knowledge Base
- https://gceasy.io - Online analysis of Java GC logs
- https://fastthread.io - Online analysis of Java thread dumps
- https://tinyurl.com/jenkins-jvm-args - Recommended JVM settings for Jenkins
- https://tinyurl.com/jenkins-thread-dump - How to get a thread dump from Jenkins
- https://www.cloudbees.com/blog/enterprise-jvm-administration-and-jenkins-performance




<details>
<summary>Introduction</summary>
<br>

  <img width="724" alt="image" src="https://user-images.githubusercontent.com/75510135/169627828-f1366650-0ceb-4659-82de-c2129a6c76ce.png">
  
  <img width="748" alt="image" src="https://user-images.githubusercontent.com/75510135/169627639-6ca2bc9e-198c-4c20-a0c2-716d5903fbd0.png">

  <img width="732" alt="image" src="https://user-images.githubusercontent.com/75510135/169627763-111184cb-8b51-495a-bbc0-c0e149e2cf2f.png">

  
</details>

<details>
<summary>Macro vs Micro Matrics</summary>
<br>

  <img width="720" alt="image" src="https://user-images.githubusercontent.com/75510135/169627878-bcfa51af-8e32-43b3-99cc-dc1b2722d02d.png">

  <img width="611" alt="image" src="https://user-images.githubusercontent.com/75510135/169627903-fd4f2019-94f8-4ad6-a7b9-7c9b66717f53.png">

  <img width="720" alt="image" src="https://user-images.githubusercontent.com/75510135/169627925-d60a6847-e5fd-4501-b98f-40dcb488e222.png">

  <img width="684" alt="image" src="https://user-images.githubusercontent.com/75510135/169627982-337b2c02-f6d1-487e-bfc2-b240b282d041.png">

  <img width="697" alt="image" src="https://user-images.githubusercontent.com/75510135/169628024-7bcc09a3-ed85-4185-9431-9fac1c862015.png">

  
</details>

<details>
<summary>Challenges</summary>
<br>

  <img width="780" alt="image" src="https://user-images.githubusercontent.com/75510135/169628066-2385b1f3-d706-41f5-9029-e780a5183e63.png">

  <img width="677" alt="image" src="https://user-images.githubusercontent.com/75510135/169628271-2f5533cf-3717-4e94-96d4-229449e23220.png">

  <img width="652" alt="image" src="https://user-images.githubusercontent.com/75510135/169628332-a2767381-1d6e-4692-954d-de995fc9252a.png">

  <img width="696" alt="image" src="https://user-images.githubusercontent.com/75510135/169628346-a28ee590-e948-4a11-95d0-3265e3020ec9.png">

  <img width="691" alt="image" src="https://user-images.githubusercontent.com/75510135/169628356-1941a18f-0fdf-4226-992e-9f3ab4d38d1f.png">

  <img width="684" alt="image" src="https://user-images.githubusercontent.com/75510135/169628363-b8538112-4d06-4d56-9af4-7052810f44bb.png">

  <img width="571" alt="image" src="https://user-images.githubusercontent.com/75510135/169628377-c1cb60fd-3779-4035-958d-e90a4c329295.png">

  <img width="630" alt="image" src="https://user-images.githubusercontent.com/75510135/169628385-b55d14fb-a483-4512-b7fc-a3d651254b59.png">

  <img width="755" alt="image" src="https://user-images.githubusercontent.com/75510135/169628396-f96c8d4f-2516-42a3-815b-58d4e67a1171.png">

  <img width="657" alt="image" src="https://user-images.githubusercontent.com/75510135/169628401-afd11c9f-c803-4081-b565-8e752da8452c.png">

  <img width="644" alt="image" src="https://user-images.githubusercontent.com/75510135/169628409-f2288404-b256-432f-9b64-b614f24caf92.png">

  <img width="721" alt="image" src="https://user-images.githubusercontent.com/75510135/169628418-3e649e50-333d-4b25-8a99-8624dc25b759.png">

  <img width="608" alt="image" src="https://user-images.githubusercontent.com/75510135/169628435-f5c27f5b-5fea-40c8-aaf6-7e22eec0c7b6.png">

  <img width="681" alt="image" src="https://user-images.githubusercontent.com/75510135/169628461-7931b297-5d64-4d86-a221-3fa020c89600.png">

  <img width="734" alt="image" src="https://user-images.githubusercontent.com/75510135/169628466-6473755f-dff8-49e8-9581-2f356c8d86ec.png">

  <img width="783" alt="image" src="https://user-images.githubusercontent.com/75510135/169628593-390bd9e6-3070-4cd6-aabd-e525697bd35b.png">

  
</details>

<details>
<summary>Real world example</summary>
<br>

  <img width="739" alt="image" src="https://user-images.githubusercontent.com/75510135/169628624-809091df-75a4-4aaa-88b2-f4eeb1af8489.png">

  <img width="751" alt="image" src="https://user-images.githubusercontent.com/75510135/169628634-19e178a6-b59b-4606-840d-0e6b0b2635b4.png">

  <img width="717" alt="image" src="https://user-images.githubusercontent.com/75510135/169628646-1d262fd1-7662-4201-8889-25427b5dca7e.png">

  <img width="746" alt="image" src="https://user-images.githubusercontent.com/75510135/169628658-bf92ffdb-f282-4375-8a40-f8dcdfe95825.png">

  <img width="768" alt="image" src="https://user-images.githubusercontent.com/75510135/169628669-b07c240d-2096-445d-9641-fe01fdfecb3b.png">

  <img width="786" alt="image" src="https://user-images.githubusercontent.com/75510135/169628687-d4890eab-9a94-4136-80a3-47bcb90f8b5a.png">

  <img width="703" alt="image" src="https://user-images.githubusercontent.com/75510135/169628704-cd187d30-d00d-4081-8beb-310d06a2eb11.png">

  <img width="592" alt="image" src="https://user-images.githubusercontent.com/75510135/169628719-a494a8c7-14b7-4ca5-9b26-22dcd1d622a2.png">

  
</details>