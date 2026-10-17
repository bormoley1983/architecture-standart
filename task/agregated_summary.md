Bank Standard
Digital transformation - extension of online channels functionality

Evaluate existing processes and plan changes

ABS - main ban system (automated banking system)
employees are working directly with it
-history of accounts operations
-accounting

internet-banking website
(customers rearly use it)
-wire payments transfers (direct integration with ABS !through database!)
-opening accounts for debit cards only (direct integration with ABS  !through database!)
-can display marketing info

Bank Call center system

Partner Call center system
using existing call scripts deployed by bank business partners

Company structure

Front-office (customer service desk)
direct contact with customer
marketing
sales

Back-office
stock
bank actives/passives management
internal busiiness processes support

(Top management) >
Bank priorities (operations directions)
-In-bank services (500 emlpoyees in 50 departments)
-IT management (IBank: 10 emlpoyees inhouse + 10 Affiliate outsource; ABS 20 employees)
-Deposit products management (50 emlpoyees)
-Credits management (50 emlpoyees)
-Bank Call center (200 emlpoyees)
-Affiliate call center (100 emlpoyees)
-Digital transformation of retail (10 employees)

IBank
Client server system
ASP .NET MVC 4.5 .Net framework 4.5
MS SQL
utilizes affiliates platform >
operated in one datacenter
reserve Datacenter by sqitching the traffic from main in case of failure

ABS
Desktop client
Delphi
Oracle
Logics > precedure oriented PL-SQL
developed inside of bank

Call-center
Client server system
Affiliate platform/tech stack
can automate CRM solutions
bank uses only call-center feature
React.js
Java + Spring boot
PostgreSQL (microservices)
on bank hardware/infra
Bank developers are java stack

Affifliate call-center
External system, shared with other companies

telecom operator
External SMS gateway

Web-site
self-developed
PHP + React.js

Busines problems
bank needs to envolve more customers (younger categories)
priorities:
-online channes development
-needs digital transformation

Plans

IBank 
- add possibility to open deposits and savings accounts

Web-site
- allow deposit quotes

Busiines golas
Intermediate state (in 6 month)
-Customers can open deposits or savings accounts inside of ibank
-MVP state: Back-office reviews deposit according existing process

Final state (in 12 month)
-Customers can open deposits or savings accounts inside of ibank
-process fully automated, back-office has no need to participate in process
-Customer quotes operated only by Front-office operators
-decrease operation costs of debit dept

Homework tasks:
1. IT landscape map and integration schema of apps
2. FURPS+ (deliverables: table of requirements split by groups)
3. Opening deposits online (ADR)
4. deposit details transfer to call-centers (ADR describing architectural solution, list of tasks for each system from new case ADR)