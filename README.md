# CMPG323_Project2_39909476
This is Bernard Swanepoel 39909476 API project for CMPG323 project2.

# Work did on 2023/08/17

Did the following tasks:

- Created the repository.
- Cloned the github repository. 
- Scaffolded the database into the project.
- Applied dependancy injection.
- Created all of the relevant methods.
- Added the reference list.
- Created the branches.
- Updated the kanban project on what has been done

# Planned work 2023/08/19

- Host a database on azure and host the app on azure.


# Work did on 2023/08/19

Did the following tasks:

- Created my azure account.
- Created the sql-database.
- Created the sql-database-server.
- Added my credentials to SSMS.
- Ran the script to create the tables in the database.
- Added data to the database.
- Created the appservice.
- Published the api but got a 404 error.

# Planned work on 2023/08/20

- Fix 404 http-error

# Work did on 2023/08/20

- Opted to used CI/CD with github actions to deploy my webapp.
- I want to give credit to my brother Pieter Swanepoel for showing me how to use CI/CD with github-actions, without his assitance I probably wouldn't have had a deployed project.
- Fixed http-error 404
- Got an http-error 500 because azure database settings not correctly configured.
- Fixed http-error 500

# Planned work

- Reimplement the .gitignore file.
- Setup API management in Azure.
- Implement API mangement functions.

# How one should go about using the API

- One should pull the data from the api's endpoints and use the data for data analytics or business insights.
- This means that the data can be used to compare the performance of EcoPower-logistics with other companies that sell products in the same industry.
- This can be used as a benchmark to determine where EcoPower-logistics stands as a company in comparison with other companies.
- This also gives EcoPower-logistics a edge because they can get insight on what is going on in there own business.
- Use the get endpoints to get data from the database or to get specific data using an ID.
- Use put method to update the entire resource with data that is passed in the body payload
- Use post method to update or create a resource.
- Use patch method to midify resources.
- Use of delete method to delete resources.
  
# Bibliography( Research I did for me to be able to do this project)

- Hopkinson, I., Maude, S. and Rospocher, M., 2014, October. A simple API to the KnowledgeStore. In ISWC (Developers Workshop) (pp. 7-12).

- Lukeš, S., 2020. API for C# code generation.

- Reynders, F., 2018. Modern API Design with ASP .NET Core 2. Building Cross.

- Masse, Mark. REST API design rulebook: designing consistent RESTful web service interfaces. " O'Reilly Media, Inc.", 2011.

- Kotas, C., Naughton, T. and Imam, N., 2018, January. A comparison of Amazon Web Services and Microsoft Azure cloud platforms for high performance computing. In 2018 IEEE International Conference on Consumer Electronics (ICCE) (pp. 1-4). IEEE.

- Graham, S.T. and Liu, X., 2014, July. Critical evaluation on jclouds and cloudify abstract APIs against EC2, azure and HP-cloud. In 2014 IEEE 38th International Computer Software and Applications Conference Workshops (pp. 510-515). IEEE.

- Atlidakis, V., Godefroid, P. and Polishchuk, M., 2019, May. Restler: Stateful rest api fuzzing. In 2019 IEEE/ACM 41st International Conference on Software Engineering (ICSE) (pp. 748-758). IEEE.

- Stack Overflow. (n.d.). Gitignore not working. [online] Available at: https://stackoverflow.com/questions/25436312/gitignore-not-working [Accessed 19 Aug. 2023].

- WhatIs.com. (n.d.). What is a 404 Error Code? What It Means and How to Fix It. [online] Available at: https://www.techtarget.com/whatis/definition/404-status-code#:~:text=404%20error%20codes%20are%20generated [Accessed 19 Aug. 2023].

- Amazon Web Services (2023). What is an API? - API Beginner’s Guide - AWS. [online] Amazon Web Services, Inc. Available at: https://aws.amazon.com/what-is/api/.

- rolyon (n.d.). Azure documentation. [online] learn.microsoft.com. Available at: https://learn.microsoft.com/en-us/azure/?product=popular.

- Contentful. (n.d.). What is an API endpoint? [online] Available at: https://www.contentful.com/blog/api-endpoint/#:~:text=In%20summary%2C%20an%20API%20endpoint.

- Bahrami, M., Park, J., Liu, L. and Chen, W.P., 2018, April. Api learning: Applying machine learning to manage the rise of api economy. In Companion Proceedings of the The Web Conference 2018 (pp. 151-154).

- Falatah, M.M. and Batarfi, O.A., 2014. Cloud scalability considerations. International Journal of Computer Science and Engineering Survey, 5(4), p.37.

- Siriwardena, Prabath. "Advanced API Security." Apress: New York, NY, USA (2014).

- Dragoni, N., Giallorenzo, S., Lafuente, A.L., Mazzara, M., Montesi, F., Mustafin, R. and Safina, L., 2017. Microservices: yesterday, today, and tomorrow. Present and ulterior software engineering, pp.195-216.

- Wilder, Bill. Cloud architecture patterns: using microsoft azure. " O'Reilly Media, Inc.", 2012.

- Pietzuch, Peter, David Eyers, Samuel Kounev, and Brian Shand. "Towards a common api for publish/subscribe." In Proceedings of the 2007 inaugural international conference on Distributed event-based systems, pp. 152-157. 2007.

- Niveditha, B. and Kumbar, M., 2021. HTTP Error Codes of Inaccessible and Retrieved URLs in LIS Journal Articles. Library Philosophy and Practice, pp.0_1-15.

- Zaveri, A., Dastgheib, S., Wu, C., Whetzel, T., Verborgh, R., Avillach, P., Korodi, G., Terryn, R., Jagodnik, K., Assis, P. and Dumontier, M., 2017. smartAPI: towards a more intelligent network of web APIs. In The Semantic Web: 14th International Conference, ESWC 2017, Portorož, Slovenia, May 28–June 1, 2017, Proceedings, Part II 14 (pp. 154-169). Springer International Publishing.

- Kratzke, N., 2018. A brief history of cloud application architectures. Applied Sciences, 8(8), p.1368.

- Wankhede, P., Talati, M. and Chinchamalatpure, R., 2020. Comparative study of cloud platforms-microsoft azure, google cloud platform and amazon EC2. J. Res. Eng. Appl. Sci, 5(02), pp.60-64.

- Di Martino, B., Cretella, G., Esposito, A. and Sperandeo, R.G., 2014, September. Semantic representation of cloud services: a case study for microsoft windows azure. In 2014 International Conference on Intelligent Networking and Collaborative Systems (pp. 647-652). IEEE.

- Murphy, L., Kery, M.B., Alliyu, O., Macvean, A. and Myers, B.A., 2018, October. API designers in the field: Design practices and challenges for creating usable APIs. In 2018 ieee symposium on visual languages and human-centric computing (vl/hcc) (pp. 249-258). IEEE.

- Alls, J., 2020. Clean Code in C#: Refactor your legacy C# code base and improve application performance by applying best practices. Packt Publishing Ltd.

‌
