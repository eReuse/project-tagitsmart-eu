# Meeting at University of Padua February 2018

**Deliverable Status:** working  
**Deliverable Number:** D2.1  
**Deliverable Due Month:** M2  
**Deliverable WP Number**: 2   
**Deliverable File**:   
**Executive Summary**:

This deliverable defines the main aspects requested by the tag it smart consortium. These are:

* SmartTags you need, because there are limitations on what can be printed so it is good from the very beginning to confirm feasibility and if needed provide alternatives. 
* Modules from TagItSmart you foresee as needed and how/why so we find needed technical contacts from the project to be assisting you in the future and also clarify on the spot any questions you may have at this point. 
* Some ecosystem/exploitation directions so we can also help you in that part.

| Call Identifier: | TagItSmart!02 call |
| --- | --- | --- | --- |
| Proposal full name: | Circular economy for electronics reuse |
| Proposal acronym: | eReuse |
| Project URL | http://www.ereuse.org |

| Grant Agreement number: | 688061 |
| --- | --- | --- | --- | --- | --- |
| Project acronym: | TagItSmart! |
| Project title: | Smart Tags driven service platform for enabling ecosystems of connected objects |
| Project website address: | ​[http://tagitsmart.eu/](http://tagitsmart.eu/)​ |
| Start Date of the Project: | 1 January 2016 |
| Duration: | 36 Months |

| Editor: | Xavier Bustamante                                                                                                                      |
| --- | --- | --- | --- | --- | --- |
| Deliverable nature | Report \(R\) |
| Dissemination level: | Public \(PU\) |
| Delivery Date | 4-2018 |
| Authors | Xavier Bustamante |
| Contributors | David Franquesa |

## **Executive Summary**:

This deliverable defines the main aspects requested by the tag it smart consortium. These are:

* SmartTags you need, because there are limitations on what can be printed so it is good from the very beginning to confirm feasibility and if needed provide alternatives. 
* Modules from TagItSmart you foresee as needed and how/why so we find needed technical contacts from the project to be assisting you in the future and also clarify on the spot any questions you may have at this point. 
* Some ecosystem/exploitation directions so we can also help you in that part.

### Describe the core idea of your project as briefly as possible

Digital devices, also referred as electric and electronic equipment \(EEE\), are relevant examples of "slow moving" circular goods \(SMCG\) that, from a circular economy perspective, can have a long usable life. The longer the better for the economy and the environment because increase lifecycle impacts on reducing TCO, increase waste prevention, used products are affordable for low income sectors, and product as a service approach may generate 3-4 more turnover than original purchase with local services including repairs, servicing, diagnostics, technical support, installation and warranty.

The core idea is the development of the “circular economy” use case for SMCG that are reusable, repairable, upgradeable, with internal replaceable parts. After repair and testing by authorized agents, refurbished products go back to the supply chain. The main impact comes from the definition of a key use case for circular economy of SMCG, the extension of the TIS platform to cover this use case, and the development and piloting of business models and solutions for this sector with a large and growing business need, and public interest.

### **What  problem exists and you are trying to solve**

1. How to ensure to device donors the chain of custody from origin \(ITAD\), during multiple cycles of reuse and until final recycling at component level \(Term "Chain of custody" of eReuse License\)?
2. How to ensure the correct application of the waste hierarchy \(Circular Economy\) in such a way that only are recycled products with low use value and without demand \(Term "Value in Chain" of eReuse License\)?
3. How to ensure consumers of used products that purchase properly refurbished products with right to repair permission, maximum selling price in the case of subsidised products and an established take-back collection process \(Term "Right to Repair", "Cost Based Price", ""\)?
4. How to avoid leakage by preventing the export of electronic waste or unauthorized agents have made the preparation for reuse?

### **Describe briefly your solution/product/service to solve it**

DeviceTag.io is a service provided by Pangea, based on eReuse.org components, that offers a platform agnostic and open-source traceability solutions for managing reusing and ensuring recycling of digital devices -such as phones or computers. The service tags each device and tracks devices throughout their full life-span, down to component level, keeping track of their way through other organizations, locations, and changes in their components. This service assist in dealing with each device by:

1. Collects device component characteristics and status, creating a non-modifiable and auditable document that contains: hardware characteristics, operating status, component tests and benchmarks, visual picture _\(under dev.\)_, aesthetic score \(machine learning\) _\(under dev.\)_ , usage value score \(community consensus algorithm\); 
2. Certifying improvements done such as removed/added components, reliably erasing its data and reinstalling the OS, 
3. Managing and sharing devices using a web inventory with a url linked to products storing its certifications \(status, reburbishment process, optimal/subsidized price, warranty, preparation for reuse,..\), 
4. Maintain and online repository subscribed to IOT services about the status and usage of devices \(faults, hours of use, collecting location, conversion to waste, etc.\).. 

### **What is the main innovation in your approach**

The DeviceTag.io is creating core circular business service and data for ITAD/refurbishers/retailers/recyclers and IT maintenance companies responsible for extending the lifespan of devices in use. Everything developed by DeviceTag.io is shared with the eReuse.org community and our service implements the ereuse.org protocol that certifies refurbishment \(and preparation for reuse\) process, chain of custody \(transfers\), circularity performance \(waste hierarchy aplication by storing value of use in the recycling process\). This is protecting consumers of buying/selling non-functional or non-reparable digital devices, boosting confidence between businesses to exchange certified data about the digital devices they want to exchange, making product-as-a-service business more viable and certifying non **premature recycling** of circular economy platforms and business.

### Describe briefly the TagItSmart modules and interactions you foresee as needed

1. Our QR label cannot be protected from forgery \[Photochromic tags?\]: a\) generating labels that seem like ours \(brand protection\) and b\) duplicating existing ones through scanning.
2. We need to input in our smarpthone App the identifier of a device fast and without error, in logistics and refurbishment processes. If the input is done manually by the operator is prone to human errors \(undoing them is very costly and require supervision\), and the operator is tempted to do it if the automatic input speed is not enough. At the moment we scan QR codes printed in black on a translucent plastic tag. This has few problems: 1. Smartphones need to access to the camera, focus and interpret the image, which is quite time consuming, and the quality of the smartphone greatly impacts timing. 2. Reading speed is impacted by lightning conditions. These tags are a bit hidden so they don't impact the aesthetics of the computer, which usually makes it difficult to reach and direct a spot of light to them 3. Scanning and reading is quite difficult on black surfaces, but white tags are not pleasant to see in dark surfaces thus increasing the chance for the final user to remove them. \[Use NFC?\]
3. We need to account which devices are in a package or pallet, specially when receiving, sending and transporting them, as a way to avoid loosing or wrongly sending them. We want too to be able to find devices in the warehouse. Tags may be hidden in packaging or under other devices. \[Use RFID with greater radius and traversing metals?\]
4. Labels have to firmly stick on device surfaces and be resistant to avoid being removed or broken due friction, usual in processes like transporting or with mobile devices like laptops. Our actual labels can be easily unstuck in some computer surfaces because of the material and painting used. We may still be able to remove them without excessive problem or breaking them, for example when a refurbisher wants to re-paint or clean the surface of the device where the label is stuck.
5. We want to know if devices are products or waste in an easy and fast way –without using a machine for it. This way consumers, operators and auditors can know if devices are waste or products, always allowing them to read the QR / NFC tag to securely verify some of the devices. \[Being able to mark on one part of the label when a product becomes waste \(a licht, a pen, ...\) and to be able to recover or put over the mark a new label when it is being prepared for reuse / repaint with an RFID marker pen that includes waste manager identification / ....\]
6. Our prototype called photobox \(a device that takes pictures of the products\) cannot certify the relationship between the photograph and the product photographed. \[Solution: once the photographed process is started it cannot stop \(the door of the photobox must remain closed\) and the object inside is read with an rfid reader \(so we assure that it is really the object to which we take pictures\)\]
7. Find illegal exports and device leakage, and generate insights and indicators about reusing. Our traceability software is decentralized; platforms are autonomous and cooperate exchanging devices. We made a prototype called [Global Record of Devices](https://github.com/eReuse/grd) as a central system that accounts transactions and records traceability information in order to detect leakage. However, there is no business model that allows its development and maintenance. Platforms require at least two services/tools, 1\) an integration with blockchain, and 2\) a data aggregator/cross-checking/monitoring subscription service where to report local data, to be used by potential actors \(waste agencies, manufacturers, previous owners, communities, etc...\) \[Everything?\].
8. The participating organizations \(refurbishers, retailers, recyclers\) define the collection and whether the collectors who make the collection and preparation for reuse are authorised or not to manage waste. There is no global directory and shared with these managers. In the past ereuse promoted the development of the DCP \([Directory of Collection Points](https://github.com/eReuse/dcp)\), however we don't plan on continuing further development in order to focus in our core software. It is desirable to find agreements with entities that perform this task. Dondelotiro can be useful for this requirement.

### F**or future**

1. How to know if a digital device \(mobile, desktop,...\) has lost its identifying tag. \[Is it possible to do the auto-reading using a mobile app?\]

## Tag proposal

A plastic translucent tag with black ink, NFC and medium-range RFID embedded technology.

1. QR code with the device URL so final users can use the phone camera.
2. Veracity challenge as an eReuse.org _e_ logo made with photocromatic inks.
3. Device identifier as a visual fallback.
4. Waste symbol that only appears when an user or a collector marks it to indicate that the device is waste. eReuse.org refurbishers are the only ones having small tags containing the _Prepared_ word or symbol, and they stick them on the waste symbol to indicate that the device is a refurbished product.

Say that users with bad intentions could remove the _Prepared_ tag, however they would only lower the value of the product thus not making sense.

A second proposal is to remove the QR code to reduce tag size. This proposal asumes all members of the eReuse.org community and final users have access to Smartphones with NFC tags.  


### **System architecture**

1. Refurbishers, ITAD and recyclers account, transport and refurbish devices using the eReuse.org Workbench toolset. The Workbench erases hard-drives, takes device information like serial numbers, takes pictures with Photobox to assess aesthetics, and manages logistics through an Android App. This results in a device ready for being re-used with a physical and a digital tag. The digital tag contains a report of the process on the device, whereas the physical tag is the SmartITTag that points to the digital identity of the device.
2. Organizacions in the eReuse.org community upload the digital tags in the DeviceHub software, an IT Asset management software in the cloud, creating or updating the digital identity of the device.
3. Upload traceability information to Everythng \[...\]

### **Everythng modules**

* _Virtual Entity Access Interface_ and _Identity Management_ to create and manage devices and traceability actions.
* _Data analytics_ to generate insights and indicators about traceability and refurbishing.
* _User Management/Authentication/Access Control_ to allow organizations to upload device traceability and access analytics.

From internal Everythng modules, we specially use _Reactor_ to program the accountant that checks for leakage and custom widgets to provide highly customized analytics.

\(We could link to [the eReuse.org tag](https://tree.taiga.io/project/devicetag/us/15?no-milestone=1) or should I import more things from there?\)

### Schedule

1. Define and order tags \(March\).
2. System prototype integrating eReuse.org to TIS \(31 May\).
3. Start pilot 0, internal. \(1 May to 31 May\).
4. Start pilot 1, with stakeholders. \(15 June to 31 July\).
   * 200 desktops \(considered products\) in one refurbisher two retailers \(of type digital divide initiative\).

### Main three stakeholders involved

Pilot project 1:

1. ITAD: Owner of devices, data security and compliance, chain of custody until recycling.
2. REFURBISHERS: collection to ITADs, add tags, certificate refurbishment process \(if waste certify the preparation for reuse process\), share their certified stocks with retailers, chain of custody until retailer.
3. RETAILER. purchase refurbished to REFURBISHERS and sell to consumers, assess the state of functioning and features of computers in order to offer warranty or its extension, we will do the pilot with a retailer of type \(public or NGOs\), similar to retailers, but must guarantee a fair pricing to receivers, with a minimal charge for circularity services to support economically disadvantaged recipients while ensuring traceability until final recycling.
4. RECYCLER: being able to offer their collection services to REFURBISHERS or RETAILERS, reporting systems to the competent authorities.

## KPIs you want to achieve

### **KPI1**

\(TIS\). Usage of SmartTags and TIS modules and extensions, adapt and Integrate eReuse.org key modules to TIS, Deployment of use case business needs, Define partnerships with TIS partners \(IPR/path to market\).

#### **Outcomes**

* KPI1.1 \(3M\)
  * Smarttag \(photocromic, RFID, NFC...\)
  * Evrythng \(as grd\)
  * dondelotiro \(as dcp\)
* KPI1.2 \(month 5\), the following features are available in the system. 
  * ITADs \(donors\) include tags at the time of donation and/or refurbishers do it.
  * Refurbishers mark as waste what has not been repaired or it is not potentially reusable.
  * Recyclers prepare for reuse devices considered as waste or finally recycle what is waste.
  * Retailers sell devices that has been refurbished and/or prepared for reuse.
* KPI1.3
  * Agreements with evrythng, dondelotiro, others...

### **KPI2**

\(Pilot/Market\). Run at pilot experiment with partners for an evaluation of feasibility \(technical and commercial\), training agents, achievable quality, process improvement, cost, margin for service fees, market in each scenario, evaluate TIS adoption by eReuse.org community, business model.

#### Outcomes.

* KPI2.1, 
  * at least 200 devices to test the tags and integrations
* KPI2.2 \(5 customers\)
  * stakeholders accept to use smartags
  * barcelona activa
  * solidança
  * donalo
  * acsrecycling
  * abacus
* KPI 2.3 
  * 5% platform usage
    * registered devices
    * snaphots
    * transfers \(between refurbisher and retailer\)
    * set product as waste
    * disposal \( waste is definitely recyled\)
  * customer satisfaction
    * 50% of entities participating in the pilot project are satisfied with the results and will recomend it to others

### **KPI3**

\(Circular Economy\). Engage the eReuse.org community on TIS integration, present papers at circular economy conferences, explain circular economy impact and marketing activities explaining TIS integration.

#### **Outcomes**

* KPI3.1
  * 1 paper
  * 1 conference
  * 2 co-desing sessions with the community
* KPI3.2
  * 6000€
* KPI3.3
  * Agència de residus
  * Generalitat de Catalunya
  * AEREES
  * ...

#### 

