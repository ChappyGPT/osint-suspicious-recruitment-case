# Methodology  

---

## Approach  

This investigation was conducted following a **non-intrusive OSINT methodology**, focused exclusively on publicly available information and provided materials.  

No intrusive techniques, impersonation, or unauthorized access were used at any stage.  

The analysis was based on:  

- Passive data collection  
- Cross-source correlation  
- Behavioral pattern identification  

The objective was not to attribute identities, but to **understand the operational structure and relationships between observed elements**.  

---

## Investigation Strategy  

The investigation followed a pivot-based approach, where key elements were used as entry points to expand the analysis.  

---

### 1. Phone Number Pivoting  

Phone numbers were treated as the **primary investigative pivot**, acting as the central node of the activity.  

#### Actions performed  

- Searching phone numbers across search engines  
- Identifying presence in social media platforms  
- Reviewing mentions in forums and third-party sites  
- Correlating multiple numbers across contexts  

#### Outcome  

- Identification of recurring numbers  
- Detection of number rotation over time  
- Establishment of phone numbers as the **core communication layer**  

---

### 2. Domain & Infrastructure Analysis  

The domain `miramedesdecasa.com` was analyzed to assess technical infrastructure.  

#### Actions performed  

- DNS resolution checks (`dig`)  
- Subdomain and certificate search (`theHarvester`, crt.sh)  
- Infrastructure correlation (SpiderFoot)  
- Service availability verification  

#### Outcome  

- Domain status: **NXDOMAIN**  
- No active services or infrastructure  
- Identification of shared hosting (199.34.228.159)  

#### Interpretation  

The infrastructure is **minimal, non-persistent, and likely disposable**, indicating that the operation does not rely on technical assets.  

---

### 3. Cross-Platform Correlation  

Multiple platforms were analyzed to identify connections between entities:  

- Social media (**Twitter/X, Facebook**)  
- Forums (**Spalumi**)  
- Search engine results (Google)  
- Web listings and service pages  

#### Focus  

- Repetition of identifiers (phone, domain, email)  
- Similar wording and structure  
- Reuse of content across platforms  

#### Outcome  

This enabled the identification of a **consistent and repeatable operational pattern across environments**.  

---

### 4. Content & Behavioral Analysis  

Content from job advertisements, posts, and communications was analyzed to understand behavior.  

#### Focus  

- Language used in recruitment posts  
- Target audience  
- Message progression  
- Type of services implied  

#### Key Observations  

- Use of **ambiguous terminology** (e.g., “massage”)  
- Gradual shift toward **service-related context**  
- Consistent structure across posts and platforms  

#### Outcome  

This allowed the reconstruction of a **recruitment funnel and interaction flow**.  

---

### 5. Direct Evidence Analysis  

In addition to public sources, **provided message exchanges and screenshots** were analyzed.  

#### Scope  

- WhatsApp conversations  
- Contact profiles linked to phone numbers  
- Payment-related interactions  

#### Focus  

- Communication style  
- Payment behavior  
- Consistency with external testimonies  

#### Key Observations  

- Repeated **payment delays and excuses**  
- Informal or undefined working conditions  
- Avoidance patterns in communication  

#### Interpretation  

These elements provide **behavioral confirmation** of patterns observed in external sources, strengthening the overall analysis.  

---

### 6. Tool-Based OSINT Analysis  

Several OSINT tools were used to support and validate findings:  

- **SpiderFoot** → infrastructure & correlation  
- **theHarvester** → domain enumeration  
- **Holehe** → email usage detection  
- **Maigret** → username enumeration  

#### Purpose  

- Identify infrastructure  
- Detect linked accounts  
- Discover reusable identifiers  

#### Outcome  

- No strong identity correlations  
- Minimal infrastructure findings  
- High noise levels (false positives)  

#### Interpretation  

The lack of results is itself relevant, indicating:  

- Fragmented identity usage  
- Lack of persistent digital footprint  

---

## Analytical Principles  

The investigation followed core OSINT principles:  

- **Passive data collection only**  
- **Correlation over assumption**  
- **Cross-source validation**  
- **No attribution without evidence**  

All conclusions were derived from **patterns and repeated indicators**, not isolated data points.  

---

## Limitations  

Several constraints impacted the investigation:  

- Inactive domain (no live infrastructure analysis possible)  
- Some phone numbers no longer active  
- Lack of persistent usernames  
- Shared hosting limits attribution  
- Noise and limitations in automated OSINT tools  

These limitations are consistent with an **evasive and non-persistent operational model**.  

---

## Conclusion  

The methodology focused on identifying relationships between **fragmented but recurring elements**, rather than relying on direct identifiers.  

Despite limited infrastructure and lack of persistent identity, it was possible to:  

- Identify a central communication node  
- Detect number rotation over time  
- Correlate activity across multiple platforms  
- Reconstruct the operational workflow  

This demonstrates that OSINT can be effective even when the target is designed to **minimize traceability and persistence**.  