# Sýn og Afmörkun 

## Númer teymis og höfundar
Hópur 0, Ebba Þóra Hvannberg

## Heiti kerfis
Cafeteria and Ordering system (COS)


## Efnisyfirlit 
- [Breytingasaga](#revision-history)
- [1. Viðskiptakröfur](#1-business-requirements)
    - [1.1 Bakgrunnur](#11-background)
    - [1.2 Viðskiptatækifæri](#12-business-opportunity)
    - [1.3 Viðskiptamarkmið](#13-business-objectives)
    - [1.4 Árangursmælikvarðar ](#14-success-metrics)
    - [1.5 Sýn](#15-vision-statement)
    - [1.6 Viðskiptaáhætta](#16-business-risks)
    - [1.7 Viðskiptaforsendur og háðleiki](#17-business-assumptions-and-dependencies)
- [2. Umfang og takmarkanir](#2-scope-and-limitations)
    - [2.1 Helstu fídusar](#21-major-features)
    - [2.2 Umfang fyrstu útgáfu](#22-scope-of-initial-and-subsequent-releases)
    - [2.3 Takmarkanir og útilokanir](#23-limitations-and-exclusions)
- [3. Samhengi viðskipta](#3-business-context)
    - [3.1 Prófílar hagsmunaaðila](#31-stakeholder-profiles)
    - [3.2 Forgangsröðun verkefnis](#32-project-priorities)
    - [3.3 Innleiðingarsjónarmið](#33-deployment-considerations)

---
> Hver kafli á að vera um það bil hálf síða að lengd.
> 
## 1. Viðskiptakröfur
### 1.1 Bakgrunnur


### 1.2 Viðskiptatækifæri


### 1.3 Viðskiptamarkmið
BO-1: Reduce the cost of cafeteria food wastage by 40% within 6 months following initial release.
 - Scale: Cost of food thrown away each week by cafeteria staff
 - Meter: Examination of Cafeteria Inventory System logs
 - Past (Baseline): 33% (2013, initial study)
 - Goal: Less than 20%
 - Stretch: Less than 15%

BO-2: Reduce cafeteria operating costs by 15% within 12 months following initial release.
 - Scale: Cost of operations per month, includes salary, all resources such as food and consumables, maintenance cost of equipment, lease (including electricity, water and heat). Excludes
   equipment purchase that are not consumable.
-  Meter: As registered in the financial accounting system
 - Past (Baseline): $10,000 for 50 persons, breakfast and lunch 
 - Goal: $8,500 per month 
 - Stretch: $8,000 per month 

BO-3: Increase average effective work time by 15 minutes per cafeteria-using employee per day within 6 months following initial release.
- Scale: Average number of minutes at the desk or in meetings per day 
- Meter: Measured by Teams activity data, including presence and meeting calendar 
- Past (Baseline): 400 minutes a day 
- Goal: 415 minutes a day 
- Stretch: 420 minutes a day 

### 1.4 Árangurs mælikvarðar


### 1.5 Framtíðarsýn
**For** employees **who** want to order meals from the company cafeteria or from local restaurants on-line, **the Cafeteria Ordering System**
**is** an Internet-based and smartphone-enabled application **that** will accept individual or group meal orders, process payments, 
and trigger delivery of the prepared meals to a designated location on the Process Impact campus. 
**Unlike** the current telephone and manual ordering processes, employees who use **the Cafeteria Ordering System** will not 
have to go to the cafeteria to get their meals, which will save them time and will increase the food choices available to them.

### 1.6 Viðskiptaáhætta


### 1.7 Viðskiptaforsendur og háðleiki


---

## 2. Umfang  og takmarkanir 
### 2.1 Helstu fídusar


FE-1:	Order and pay for meals from the cafeteria menu to be picked up or delivered.
FE-2:	Order and pay for meals from local restaurants to be delivered.
FE-3:	Create, view, modify, and cancel meal subscriptions for standing or recurring meal orders, or for daily special meals.
FE-4:	Create, view, modify, delete, and archive cafeteria menus.
FE-5:	View ingredient lists and nutritional information for cafeteria menu items.
FE-6:	Provide system access through corporate intranet, smartphone, tablet, and outside Internet access by authorized employees

[Mynd Feature tree ](myndir/FeatureTree.png)

### 2.2 Umfang fyrstu útgáfu

# Feature Comparison by Release

| Feature | Release 1 | Release 2 | Release 3 |
|----------|------------|------------|------------|
| **FE-1, Order from cafeteria** | Standard meals from lunch menu only; meal orders for delivery can be paid for only by payroll deduction | Accept credit and debit card payments | Accept meal orders for breakfasts and suppers |
| **FE-2, Order from restaurants** | Not implemented | Delivery to campus locations only | Fully implemented |
| **FE-3, Meal subscriptions** | Not implemented | Implemented if time permits | Fully implemented |
| **FE-4, Menus** | Create and view menus | Modify, delete, and archive menus |  |
| **FE-5, Ingredient lists** | Not implemented | Fully implemented |  |
| **FE-6, System access** | Intranet and outside Internet access | iOS and Android phone and tablet apps | Windows Phone and tablet apps |

### 2.3 Takmarkanir og útilokanir


---

## 3. Samhengi viðskipta
### 3.1 Prófílar forgangs hagsmunaaðila

| Stakeholder | Major Value | Attitudes | Major Interests | Constraints |
|--------------|--------------|------------|------------------|--------------|
| **Corporate Management** | Improved employee productivity; cost savings for cafeteria | Strong commitment through release 2; support for release 3 contingent on earlier results | Cost and employee time savings must exceed development and usage costs | None identified |
| **Cafeteria Staff** | More efficient use of staff time throughout the day; higher customer satisfaction | Concern about union relationships and possible downsizing; otherwise receptive | Job preservation | Training for staff in Internet usage needed; delivery staff and vehicles needed |
| **Patrons** | Better food selection; time savings; convenience | Strong enthusiasm, but might not use it as much as expected because of social value of eating lunches in cafeteria and restaurants | Simplicity of use; reliability of delivery; availability of food choices | Corporate intranet access, Internet access, or a mobile device is needed |
| **Payroll Department** | No benefit; needs to set up payroll deduction registration scheme | Not happy about the software work needed, but recognizes the value to the company and employees | Minimal changes in current payroll applications | No resources yet committed to make software changes |
| **Restaurant Managers** | Increased sales; marketing exposure to generate new customers | Receptive but cautious | Minimal new technology needed; concern about resources and costs of delivering meals | Might not have staff and capacity to handle order levels; might not have all menus online |


### 3.2 Forgangsröðun verkefnis 


### 3.3 Innleiðingarsjónarmið 


## Breytingasaga
<!--
Í stað þess að halda utan um alla commit-sögu er aðeins skráð formleg útgáfa (milestones) með Git tags (merkjum).  
Hver lína í töflunni samsvarar tag (merki) sem hefur verið sett í Git repositoryið.
> 🔖 Revision History er viðhaldið með **Git tags**.  
> Þegar ný útgáfa (t.d. drög eða baseline) er tilbúin, búið til tag í Git (`git tag -a vX.Y -m "message" && git push origin vX.Y`)  
> sem bætir einni línu við í töfluna hér að neðan.
-->
> 🔖 Taflan hér á eftir er búin til með því að keyra shell skrána `updatevisionhistory.sh` í bash terminal
> 
>  `chmod +x updatevisionhistory.sh`
> 
>  `./updatevisionhistory.sh`
> 
>  Ef þú vilt skoða töfluna fyrst til að sjá hvernig hún kemur út geturðu gert eftirfarandi beint úr skelinni 
> `git log -n 5 --pretty=format:"| %an | %ad | %s | %h |" --date=short -n 10 -- VISIONSCOPE.md`


<!-- GIT_HISTORY_START -->
| Author | Date       | Message | Commit |
|--------|------------|---------|--------|
| Ebba Þóra Hvannberg | 2025-10-06 | Kafli 3.1 Einnig heiti kerfis og höfundur | c70a6e4 |
| Ebba Þóra Hvannberg | 2025-10-06 | Kaflar 2.1 og 2.2 | ae7212c |
| Ebba Þóra Hvannberg | 2025-10-06 | Kafli 2.1 Umfang fyrstu útgáfu Sjá issue  #4 | bafecee |
| Ebba Þóra Hvannberg | 2025-10-06 | Kafli 1.5 Vision Statement - Framtíðarsýn | b844b70 |
| Ebba Þóra Hvannberg | 2025-10-06 | Kafli 1.3. Viðskiptamarkmið #2 | d90a0f0 |
| Ebba Þóra Hvannberg | 2025-10-06 | Initial commit | 517e310 |

<!-- GIT_HISTORY_END -->

> Skoða allt: `git log -- "VISIONSCOPE.md" `
