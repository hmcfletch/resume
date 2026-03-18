# Les Fletcher's CV

- Phone: +1 604 445 9486
- Email: [les.fletcher@gmail.com](mailto:les.fletcher@gmail.com)
- Location: Vancouver, BC
- LinkedIn: [hmcfletch](https://linkedin.com/in/hmcfletch)
- GitHub: [hmcfletch](https://github.com/hmcfletch)


# Summary
I’m a software developer with a Masters in Computational Mathematics from Stanford University, a Bachelor of Science in Computer Science and Mathematics from Harvey Mudd College and 20 years of software engineering experience with start ups in Silicon Valley and in Vancouver.

I am primarily focused on the backend and related services and tools using a deep knowledge of Ruby and Rails and more recently Typescript. I have found that my passion for development lies just below the customer facing features and just above DevOps somewhere within the frameworks we all love to use. My most fulfilling work is making the lives of my fellow devs better, easier, and more joyful.

That being said, I have also have a knack for engaging with product owners to help refine features and get the most out of our systems, both existing, and soon to be created. I really enjoy helping product teams realize and understand the tradeoffs for all the options and ways forward that they didn't know existed.

Over the years I have been all over the org chart below the executive level. My roles have included IC, mentor, team lead, manager of managers, staff developer, and unofficially many more. Out of all of these, I am most effective in a senior/staff developer role, providing guidance and support, technical and otherwise, to other devs and teams. In addition, multiple levels of management experience have given me empathy and appreciation for the engineering manager role. I strive to be a boon to any manager I work with or under, knowing how difficult their tasks and burdens are. I partner well with managers to deliver the solutions needed, whether this is through helping an experienced manager refine, navigate, and deliver what is being asked of our team, or helping a newly minted team lead get their feet under them with confidence. I enjoy being an asset to a team/org and uplifting those around me.

# Education
## **Stanford University**, MS in Insititue for Computational Mathematics and Engineering -- Stanford, CASept 2004 – Apr 2006

ICME is a cross disciplinary program that spans across all 7 of Stanford's schools.

- Classes across many areas of computational mathematics including applied mathematics, algorithms, algorithm implementation, theory, data analysis, and simulation



## **Harvey Mudd College**, BS in Joint Computer Science and Mathematics -- Claremont, CASept 2000 – May 2004

A highly competetive and intense technical education with an added focus on humanities for an extensive and well-rounded education.

- Clinic project focused on running PageRank on smaller, more discrete sections of webpages

- Division III All American in the 4x100m relay in Track and Field



# Experience
## **Staff Enginner**, Later -- Vancouver, BC

Nov 2015 – Oct 2025

Later is a social media managagment service that provides scheduling, analytics, insights, and much more for small and medium business and influencers.

- Primary technologies

  - Ruby on Rails

  - Sidekiq

  - AWS

  - Typescript

- Managed and built out the backend team to roughly a dozen developers

  - Managed multiple subteams (manger of managers)

  - At our largest (pre-acquisiton), the engineering team as a whole had a near even split between men and women

  - Very successful coop program with near 75% conversion to FTE. These coops unversially ended up being key devs owning critical pieces of the product and infrastructure.

  - Significantly above average retenion

- Built out our social analytics collection engine

  - Pure Ruby/Sidekiq/SQS app with some very light ActiveSupport use

  - Processes between 20-25 million Sidekiq jobs a day

  - This service has required very little maintenance and improvements over its roughly seven year lifespan

- Mostly responsible for performance and scaling our services

  - Tuning the PostgreSQL database

  - Identifying and refactoring slow queries (pganalyze)

  - Identifying and rectifying slow endpoints and other bottlenecks (Skylight and Datadog)

- Wrote and maintaned numerous internal gems

  - A number of clients for accessing social network APIs

  - An implementaion of debounce functionality for Sidekiq jobs

  - A simplified, safer, and more performant Sidekiq Delayed functionality

  - A common interface for our new platform services

- Refined and simplified our use of Faktory (polyglot version of Sidekiq) within the platform team

- Developed a new deployment CLI and workflow to standarize the deployment process for all of our K8s/ArgoCD apps. This drastically reduced the time from PR to production and provided a smooth and convenient developer experience for interacting with deployments and environments.

- Developed on-demand image resizing infrastructure using S3 object endpoints and AWS Lambda

  - Massive reduction in AWS storage bill, in the realms of tens of thousands of dollars a month

  - Reduced bandwidth cause with use of dynamic and proper cache headers

  - Drastically simplified the image processing pipeline



## **Senior Software Developer**, Tophatter -- Palo Alto, CA

Feb 2011 – June 2015

As the first employee and a member of the Tophatter, engineering team I worked across all of our platforms. On the web side of things I worked as a backend developer with Ruby on Rails to help build out tophatter.com and the APIs for associated clients. I also worked on the early iPhone and iPad apps helping to bring the Tophatter realtime auction experience to mobile devices. I also pair programmed with an outside contractor to expand the Tophatter mobile experience to Android devices.

- Initial development and launch of the Tophatter Android application

- Managed the rollout of following Android releases

- Initial development of the iOS and iPad applications

- Pushed for and helped standardize the Tophatter mobile style guide with our UX designer

- Architected and implemented various pieces of the tophatter.com infrastructure

- Database and web app optimizations

- Rails 3.x to Rails 4.x migration

- Built out the push notification and mass mailing infrastructure



## **Senior Software Engineer**, Blippy -- Palo Alto, CA

Jan 2010 – Feb 2011

I was a Ruby on Rails developer working for the social commerce site blippy.com.

- Integrated with 3rd party APIs

- Built out our own third party API to enable an app ecosystem

- Newsfeed optimizations as the user base scaled up

- Managed structuring of data from many disparate sources



## **Software Developer**, Tagged, Inc (now if(we)) -- San Francisco, CA

Nov 2008 – July 2009

Learned how to do things at a larger scale.  Worked on the Tuning and Analytics Team as well as the Search Infrastructure Team.

- Built Java search services based off Lunece with custom ranking algorithms and assocaited PHP clients

- Managed high volume data throughput, including full-index builds

- Researched, tested, configured, deployed, and monitored search technologies

- Integrated search technologies into site-wide system monitoring tools

- Integrated search technologies into multiple recommendation systems

- Supported application integration, including construction of integration tests

- Worked on tuning and analytics, implementing A/B tests across the whole site from the invite flow, to emails, to game mechanics



## **Lead Software Engineer**, Affinity Circles -- Mountain View, CA

Jan 2006 – Oct 2008

Affinity Circles partnered with organizations to provide them with a secure and trusted social networking platform for their constituents. Affinity Circles also provided talent sourcing tools for companies looking to engage highly qualified candidates.

- Oversaw a team of 8 developers and 3 separate product pipelines

- Development done in a Perl/Catalyst/DBIC environment

- Developed the first version of the opportunity matching platform, and prototyped the proof of concept that became the second version. This platform became the central piece of technology that was used to provide value to end users and recruiting customers.

- Developed the first iterations of the search solution using Java, Tomcat, and Lucene which was in production for about a year and a half

- Mentored most of the developers that were hired after me



## **Software Engineer Intern**, Microsoft -- Redmond, WA

June 2005 – Aug 2005

Worked on Microsoft Codename Max. This was a media management app used to show off a number of new technolgies: WinFX, Avalon, Indigo, Common Language Runtime.



## **Software Engineer Intern**, Aepona Ltd. -- Belfast, Nothern Ireland

July 2004 – Sept 2004

Worked on Paraly X carrier network interface



# Skills
**Languages:** Ruby, Typescript

**Major Libraries:** Rails, NestJS, Sidekiq

**Infrastructure:** AWS, PostgreSQL, Redis

# Hobbies
Brazilain Jiu Jitsu, Brown Belt

Sambo

Running

Reading

# Open Source Projects
## **[data-attributes](https://github.com/hmcfletch/data-attributes/)**

2011

`ActiveRecord::Store` before `ActiveRecord::Store` existed



## **[select-column](https://github.com/hmcfletch/select-column/)**

2011

`#pluck` before `#pluck` existed



## **[tld-cookies](https://github.com/hmcfletch/tld-cookies/)**

2011

Allowed for easily setting cookies to be accessed across subdomains.



## **[encrypted-cookies](https://github.com/hmcfletch/encrypted-cookies/)**

2011

Easily create and use encrypted cookies



## **[encrypted-cookie-store](https://github.com/hmcfletch/encrypted-cookie-store/)**

2011

Use encrypted cookies as a session store



## **[sparse-matrix](https://github.com/hmcfletch/sparse-matrix/)**

2011

Drop in replacement for `Matrix` and `Vector` Ruby classes


