# integrity.io
Integrity.io is an idea to solve data integrity problem in health care industry using Ethereum block chain

Describe the business model including what products or services will be produced. How will money be made in terms of differentiation through innovation and/or through cost reduction by striving to be the low-cost producer? 
                  
  Integrity.io is a Software as a service application enables insurance companies to securely access and share provider information with the right permission. Integrity.io's block-chain based architecture using IOT device data allows insurance payers to maintain integrity of providers information. Generally, health insurance companies maintain providers data individually and most of them rely on third parties for data updating or validation. By having a block chain, we can communicate provider data updates across the network. Labor costs involved for single payer to collect data will be reduced by a great extent, if all the payers have access to single master data store where updates can be made by any authorized payer. 
  
Process flow: 
Providers don’t update their details regularly when they move, having GPS locator device attached to the equipment they mostly use, we can easily track their location. 
Upon detecting change in their location, we alert both provider and payer to confirm the new details. Here the payer is the top ranked single payer for that particular provider.  
Once confirmed the data will be then published to blockchain with license key of provider and public key of payer.  
This updated data will be then persisted to single master data from which other authenticated payers covering that particular provider can fetch the updates to their systems. 
 
Integrity.io can act as a single third party for a group of insurance companies by providing technological solution to maintain data integrity of providers. A reliable and scalable master data center, API to interact with single database, Ethereum block chain and GPS locator can be used together to provide service to insurance companies at a very low cost. 
  
Describe the target market and customer segments. 
  Health insurance companies in the market are our target clients. From well-established insurance companies to newly started insurance agencies can use our service. 
 
 
Who are the existing & potential competitors? 
  Existing third-party companies which collect providers data and updates payers, are our competitors. Though they are expensive, insurance companies are depending on them since long time and they may feel difficult to migrate their dependency. 
Potential competitors are new startups and existing leaders in technology, who can use similar concept to solve the problem.  
 
What are the primary barriers to entry in this market? 
  Technology is complex which requires time and efforts to complete the development of the project. Legacy systems which healthcare providers and payers use, makes it difficult for them in adopting new technological solution.  
Privacy concern of both parties. 
 
 
What will be the mantra of your organization? 
We assure providers data integrity, let payers concentrate more on their core business. 
 
Why did you choose this business and industry to compete in, why would your business be viable, what are the first steps or tactics you would take to start the business? (You need to try to fill this section up.) 
                   The health care entities are extensively using legacy systems for their day to day business functions. They experience delay and inaccuracy in data communication between providers and payers causing nearly 4 – 6% of claim errors. Block chain has emerged as a reliable and secured technology that can be leveraged for different solutions. Its use in health care industry started gaining momentum. Down the line, after 5 years, block chain might be widely used and as pioneers we want to implement its usage in healthcare industry. 
 
  Managing provider data involves manual processes such as data collection, quality check, updating the approved data and persisting the data into payer's directory. This long process requires many men hours as it require physical inspection of providers site to collect the information. Sometimes this data can be erroneous.  
The costs associated with above process can be eliminated to great extent with the use of GPS tracker and blockchain infrastructure. The data is updated to network and authorized by integrity.io. This is then updated in master data, which is accessible to other payers in the network. 
The business model proposed is zero to one in the market and this requires extensive research and development for success of the project. As initial steps, we would like to implement block chain infrastructure. Publish sample IOT device data on the network. Authenticate the data accuracy by a credentialing authorities(payers or Integrity.io). Identify best database to manage data. MongoDB can be used for its pros such as scalability, cost efficiency and flexibility. Test the security and accuracy of data.  
Once the basic working model gets ready, beta version of software can be released. 
Request payers who sign up for service to communicate their providers about the new service we offer and ask them to sign up in our application. 
Collect providers information, install GPS tracker at providers place.  
Steps in building Integrity.io: 
1.Developing Integrity.io software which is used as an interface by providers and payers to access and update data 
2.Building blockchain infrastructure using Ethereum protocol 
3.Establishing master data center 
4. Release the product and initiate marketing to gain clients  
5. Identifying clients(insurance companies) based on region and plans they offer. Forming group of network. 
6. Let provider use our application to update their data.  

 
Notes: 
Provider data is the information about a provider(ex: a doctor) contained in a provider directory, referenced during the claims process and used to determine network adequacy.  
Smart contracts can be used to automate the granting and revocation of access to providers and payers. 

 
 
![iotproject](https://user-images.githubusercontent.com/32714796/33084439-d76eb024-ce96-11e7-974a-038c5e5006c9.PNG) 
Figure 1: Conceptual model of idea where provider information is updated in block chain network and then after authentication persisted to master database.  
 
Prototype: https://marvelapp.com/46e93f9 
 
 
 

References: 
http://www.ethdocs.org/en/latest/network/connecting-to-the-network.html#the-ethereum-network 
https://www.ethereum.org/ 
