# X-ray Simulator Documentation

This context defines the shared language for the X-ray Simulator support documentation site.

## Language

**Faculty Approval Packet**:
A documentation journey for faculty or program directors who need to help internal stakeholders approve X-ray Simulator procurement. The packet points each stakeholder to the page they can review or forward.
_Avoid_: Generic procurement page, sales page

**Forwarding Checklist**:
The top-level format for the Faculty Approval Packet. It helps a Program Director quickly find approval materials for internal departments, without prescribing the institution's routing process or providing copy-paste email text.
_Avoid_: Process guide, email template library, internal routing instructions

**Program Director**:
The faculty-side buyer or sponsor who introduces X-ray Simulator to an institution and coordinates internal approval with IT, procurement, and legal stakeholders.
_Avoid_: Customer, user, admin

**Recipient Department**:
An internal institutional department that receives part of the Faculty Approval Packet for review. Current recipient departments are IT/security, procurement/purchasing, and legal/vendor onboarding.
_Avoid_: Audience, stakeholder, approver

**IT and Security Review**:
The recipient page for technical reviewers who need to understand deployment, system requirements, data handling, authentication, network needs, and MDM deployment.
_Avoid_: IT approval

**Purchasing and Equipment**:
The recipient page for procurement or purchasing teams who need to understand what is being purchased, which equipment may be needed, and how quotes, purchase orders, invoices, and licensing fit together.
_Avoid_: Equipment page, buying guide

**Vendor and Legal Review**:
The recipient page for legal, compliance, vendor management, or procurement teams who need vendor details, contract materials, privacy information, and onboarding documents.
_Avoid_: Legal approval

**Product-Specific Approval Detail**:
A short distinction inside a recipient page where Desktop X-ray Simulator and VR X-ray Simulator differ. The Faculty Approval Packet covers both products together and only splits by product when the approval information genuinely differs.
_Avoid_: Separate Desktop approval packet, separate VR approval packet

**Approval Material Tone**:
The writing style for the Faculty Approval Packet and recipient pages. It should be low-sales, factual, and easy for faculty to forward internally with confidence.
_Avoid_: Marketing page, persuasion-heavy copy

**Document Request**:
A call to action for recipient departments to request non-public procurement, legal, vendor, or security documents from VitaSim. These requests route to `sales@vitasim.dk` through a `mailto:` link.
_Avoid_: Public document library, hidden download

**Canonical Supporting Doc**:
An existing documentation page that remains the source of truth for detailed setup, deployment, hardware, or security information. Recipient pages summarize the relevance of these docs and link to them rather than rewriting the same instructions.
_Avoid_: Duplicate setup instructions, copied MDM guide, copied hardware requirements

**Public Vendor Profile**:
Minimal public vendor information suitable for a forwardable legal or vendor management page. It includes stable facts such as vendor name, product name, website, contact email, and document categories available on request.
_Avoid_: Public tax records, contract terms, insurance certificates, invented legal details

**Vendor Document Request**:
A request for non-public or institution-specific vendor review materials. Common requests include questionnaire responses, bank details for wire transfers, W-8BEN-E or other required vendor tax forms, sole source information, terms of service, and insurance information.
_Avoid_: Public download library, invented vendor forms

**Purchasing Path Summary**:
A stable overview of what an institution may need to buy for Desktop or VR use. Faculty may already have one or more quotes, and quotes may include software licenses, optional hardware, or both. The page summarizes buying paths and links to hardware requirements or example station pages instead of copying time-sensitive product links and prices.
_Avoid_: Duplicated product tables, copied prices

**IT Review Overview**:
The forwardable recipient page for IT and security teams. It summarizes deployment, data handling, authentication, network, and management considerations, then links to canonical supporting docs such as the technical/security FAQ and MDM deployment guide.
_Avoid_: Duplicated technical/security FAQ

**Common IT Review Questions**:
The recurring approval questions IT teams ask about X-ray Simulator: whether it is SaaS/browser-based, whether it is a local install, minimum requirements, MDM support, student self-service use, special ports, local server requirements, PID data, payment processing, and healthcare information.
_Avoid_: Generic security overview

**License Pricing**:
Recurring X-ray Simulator access pricing based on student count. A licensed student/user is any student expected to use X-ray Simulator during the licensed period, regardless of whether they have an individual account, share a station account, or use multiple devices. Faculty, instructors, IT reviewers, and administrators do not count toward the paid license count; they are included to support teaching, setup, review, and administration. Licenses are tied to the number of students who will use X-ray Simulator, not to the number of computers, VR stations, or login accounts. License quotes must go through `sales@vitasim.dk`.
_Avoid_: Hardware price, one-time purchase

**License Key**:
Deprecated customer-facing concept. License keys do not have a functional role in X-ray Simulator setup, account access, or license counting, and should be removed from customer-facing docs.
_Avoid_: Activation key, license key setup step

**X-ray Simulator Account**:
A login credential used to access the X-ray Simulator application. Accounts are created and provided by VitaSim after purchase. Customers request additional or replacement accounts through their CSM or support contact. Accounts are not the same thing as licenses: an institution may use individual student accounts when students should log in as themselves, or use a smaller number of shared station accounts for operational simplicity, especially on VR stations. Shared station accounts are acceptable, but individual student accounts are better when a program needs per-student tracking, separate saved progress, or clearer accountability. Either way, licensing is still based on the number of students using the simulator, not on the number of accounts.
_Avoid_: License, user license

**Student User**:
A student who uses X-ray Simulator for training. Student users determine license count, even when they share one station account for operational simplicity.
_Avoid_: Account, station

**User Terminology Rule**:
Avoid using "users" by itself when explaining licensing or login setup, because customers may read it as either student users or login accounts. Use "students" when describing license count and "accounts" when describing login credentials. Use "users" only when the sentence defines what kind of user is meant.
_Avoid_: Ambiguous users

**VR Station**:
The physical VR training setup, typically a VR-ready PC, Meta Quest headset, monitor, and Link cable. A station is hardware and does not define the license count.
_Avoid_: License, account

**Desktop and VR Account Pattern**:
Desktop deployments commonly use individual student accounts because students may run X-ray Simulator on their own machines. VR deployments commonly use station or shared accounts because the headset and PC are shared equipment. Both account patterns can be used for either product when the program prefers that setup.
_Avoid_: Desktop-only individual accounts, VR-only shared accounts

**Credential Layers**:
Accounts and login documentation must separate the different credential layers. X-ray Simulator accounts are created by VitaSim and control simulator access. Windows/PC logins are institution-managed and control access to the computer. Hardware admin logins are institution/IT-managed and used for installation, updates, MDM, and troubleshooting. Meta accounts and Meta Quest Link logins are only relevant for VR headset setup and are separate from X-ray Simulator licensing and accounts.
_Avoid_: Treating all logins as one account type

**Account and License Support Routing**:
Customers can contact `sales@vitasim.dk` for questions about X-ray Simulator accounts, license counts, and licensing. Customers can contact `support@vitasim.dk` for questions about PC logins, Meta accounts, Meta Quest Link login, or hardware admin accounts.
_Avoid_: Routing all account questions to one contact

**Hardware Purchase**:
A one-time equipment purchase for computers, VR headsets, Link cables, or station components. Institutions can either buy hardware themselves using the recommended equipment lists or request VitaSim to procure it on their behalf with a 20% hardware procurement markup.
_Avoid_: License fee, student license

**Procurement Payment Terms**:
The payment guidance for purchasing teams. VitaSim accepts purchase orders and bank transfer or wire transfer; card and check payments are accepted with a 5.25% fee. Checks should be mailed to VitaSim, Forskerparken 10, 5230 Odense M, Denmark.
_Avoid_: No-fee card payment, no-fee check payment

## Example Dialogue

Faculty: "Our program wants X-ray Simulator, but IT and procurement need information before approval."

VitaSim: "Start with the Faculty Approval Packet. Send the IT/security page to IT, the purchasing page to procurement, and the vendor onboarding page to legal or vendor management."
