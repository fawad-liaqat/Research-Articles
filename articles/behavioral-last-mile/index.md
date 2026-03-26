# The Behavioral Last Mile: Why 88% Digital Infrastructure Produces 60% Cash Economies

**Fawad Liaqat**  
BSFT, NUCES FAST Islamabad

## Abstract

**Background:** Pakistan's digital payment infrastructure has achieved remarkable scale: 88% of retail transactions flow through digital channels by volume, Raast P2P transactions grew 8.7x in three years to 1.28 billion, and over one million merchants accept QR payments. Yet over 60% of economic activity remains cash-based, 98% of ATM transactions are cash withdrawals, and only 35% of adults are financially included. This paradox reveals a fundamental gap between supply-side infrastructure deployment and demand-side behavioral adoption.

**Methods:** This study employs comparative case study methodology using publicly available quantitative data from the State Bank of Pakistan Annual Payment Systems Review FY25 and Karandaaz Financial Inclusion Survey 2024. Pakistan serves as the primary case, with India's UPI system and Kenya's M-Pesa analyzed at equivalent infrastructure deployment stages (year 5 of system launch) to isolate behavioral variables explaining divergent adoption outcomes. The analytical framework structures demand-side barriers inductively from K-FIS 2024 data and theoretical literature.

**Results:** The analysis identifies three compounding demand-side barriers that persist despite infrastructure deployment: trust deficit (only 9% of excluded adults trust banks, 8% trust mobile money), incentive misalignment (merchants face 1.5–2.5% discount fees that favor cash payment acceptance), and literacy friction (digital literacy lags smartphone penetration, particularly among women at 46% phone ownership vs. 82% for men, and in rural areas). These barriers compound multiplicatively rather than additively, creating nested adoption obstacles that infrastructure alone cannot resolve. Comparative analysis reveals India's zero MDR policy accelerated adoption 26-fold, while Kenya's agent network leveraged existing social trust mechanisms.

**Conclusions:** Five specific, precedent-backed interventions targeting behavioral barriers are proposed: eliminating merchant discount rates for transactions below PKR 5,000, redesigning payment systems for feature phone access via USSD/IVR, deploying trust intermediaries (agents) with aligned incentives for digital facilitation, creating tax incentives for documented digital spending to reframe formalization costs as benefits, and mandating Urdu-first interface design standards for financial applications. Infrastructure deployment is necessary but insufficient; deliberate behavioral policy design is essential for sustainable digital payment adoption in emerging markets.

**Keywords:** digital payments, financial inclusion, behavioral economics, Pakistan, Raast, cash persistence

---

## 1. Introduction

In fiscal year 2025, 88% of Pakistan's retail payment transactions flowed through digital channels by volume ([State Bank of Pakistan, 2025](https://www.sbp.org.pk/PS/PDF/Annual-Payment-Systems-Review-FY25.pdf)). Raast, the country's instant payment system launched in January 2021, processed 1.28 billion peer-to-peer transactions, a 157% increase over the previous year and an 8.7x increase from 147 million in FY23 ([State Bank of Pakistan, 2025](https://www.sbp.org.pk/PS/PDF/Annual-Payment-Systems-Review-FY25.pdf)). Over one million merchants now accept QR code payments. Mobile banking app transactions reached 6.2 billion, growing 52% year over year. By any infrastructure metric, Pakistan's digital payment ecosystem is scaling rapidly. The branchless banking agent network has expanded to 731,814 agents. POS terminals exceed 195,000 units deployed across merchants. Branchless banking mobile app users reached 79.2 million, representing a 35% increase from the previous year.

Yet the behavioral reality tells a fundamentally different story. Over 60% of economic activity remains cash-based, representing a dominant economic transaction mode despite years of digital infrastructure investment. Of the 20,341 ATMs operating across the country, 98% of transactions are cash withdrawals ([State Bank of Pakistan, 2025](https://www.sbp.org.pk/PS/PDF/Annual-Payment-Systems-Review-FY25.pdf)). This statistic is particularly revealing: even individuals who have overcome institutional distrust sufficiently to maintain bank accounts and possess debit cards still choose to convert their digital money to physical cash before engaging in economic activity. Financial inclusion stands at 35% of adults, up from 8% in 2013 but still among the lowest in South Asia ([Karandaaz, 2025](https://portal.karandaaz.com.pk){:target="\_blank"}). An estimated 54 million bank deposit accounts hold balances below PKR 5,000, suggesting they are functionally dormant and represent passive rather than active financial participation.

This paper addresses the fundamental gap between these two realities. The core research question is direct: why does a country with 88% digital transaction volume by channel share still operate as a predominantly cash economy? The answer, this paper argues, lies not in infrastructure deficiency—the infrastructure exists, is deployed, and processes substantial transaction volume—but in what we term the "behavioral last mile," the compounding demand-side barriers that persist after infrastructure is in place and operational.

Most academic and policy literature on digital payment adoption focuses on the supply side: building payment rails, deploying terminals, licensing wallets, establishing regulatory frameworks (Demirguc-Kunt et al., 2022). The demand side—the behavioral, institutional, and structural reasons people choose not to use infrastructure that exists—receives far less systematic analysis in the literature. Pakistan is the ideal case study because the paradox is quantified with precision, the data is publicly available from credible regulatory and research sources, and the tension between infrastructure success and behavioral stasis is acute and measurable.

The analysis is structured around three compounding layers of the behavioral last mile: trust deficit, incentive misalignment, and literacy friction. Each layer is examined with Pakistan-specific evidence and compared against India (UPI) and Kenya (M-Pesa) at equivalent infrastructure stages. The paper concludes with five specific interventions derived from the comparative analysis, each with implementation guidance and precedent from comparable markets.

---

## 2. Literature Review

The literature on digital payment adoption in developing economies clusters around two broad themes: infrastructure deployment as a driver of financial inclusion, and behavioral barriers to adoption. The gap lies in their intersection—what happens when infrastructure is deployed at scale but adoption stalls at inadequate levels.

On the supply side, the World Bank's [Global Findex database](https://www.worldbank.org/en/publication/globalfindex){:target="\_blank"} has documented the link between account ownership and infrastructure availability across six survey waves since 2011 (Demirguc-Kunt et al., 2022). The consensus finding is robust and consistent across contexts: infrastructure availability is necessary but not sufficient for meaningful adoption. Account ownership reached 79% globally by 2025, yet usage patterns vary enormously across comparable economies with similar infrastructure levels. This variance points to demand-side rather than supply-side explanations for adoption divergence.

The Technology Acceptance Model (TAM), introduced by Davis (1989), provides the foundational theoretical lens for understanding digital service adoption. TAM posits that adoption depends on two primary factors: perceived usefulness (belief that the system enhances job or life performance) and perceived ease of use (belief that the system is user-friendly). Subsequent extensions incorporate trust as a critical mediating variable, particularly relevant in contexts where institutional credibility is low (Gefen et al., 2003). In Pakistan's context, trust is not merely a mediating variable; it is a primary structural barrier to adoption.

Rogers' (2003) Diffusion of Innovations framework suggests that Pakistan's digital payment adoption may be stalled at the "chasm" between early adopters and the early majority. Rogers identifies a critical transition point: early adopters tolerate friction and complexity in exchange for the perception of advantage, but the early majority requires that benefits exceed costs and that ease of use be near-intuitive. The chasm is not a technological gap but a behavioral and institutional one.

Kahneman and Tversky's (1979) Prospect Theory offers additional explanatory power through loss aversion mechanisms. Loss aversion predicts that the perceived risk of digital transactions (potential fraud, failed transactions, irreversible money loss, tax exposure from formalization) will outweigh perceived benefits for risk-averse populations, even when an objective expected value calculation would favor digital adoption. In informal economies with histories of institutional instability, loss aversion is a rational response to actual past experience.

The canonical study on mobile money adoption remains Jack and Suri's (2014) analysis of M-Pesa in Kenya, published in the American Economic Review. Their finding that M-Pesa reduced transaction costs for domestic remittances by 96% demonstrates that adoption accelerates sharply when digital payment solves a specific, acute, quantifiable pain point. The implication for Pakistan is direct: infrastructure without a catalytic use case produces infrastructure without proportionate adoption.

Zucker's (1986) work on institutional trust provides the final theoretical anchor. In economies with low institutional trust, intermediary-based trust (agents, community figures, established shopkeepers) substitutes for institutional trust as the foundation for transactions. Kenya's agent network exemplifies this mechanism. Pakistan's Raast system, by contrast, is entirely app-based and institution-facing, requiring users to interact directly with banking institutions and their technology systems, thereby bypassing the intermediary trust layer entirely.

---

## 3. Methodology

This study employs a comparative case study methodology using publicly available quantitative data supplemented by policy analysis and regulatory documentation. Pakistan serves as the primary case study. India and Kenya serve as comparative cases at different stages of payment system maturity and policy implementation.

The Pakistan data draws from two primary sources: the [State Bank of Pakistan Annual Payment Systems Review FY25](https://www.sbp.org.pk/PS/PDF/Annual-Payment-Systems-Review-FY25.pdf){:target="\_blank"} (published November 2025), covering transaction volumes, infrastructure deployment metrics, user adoption statistics, and ATM utilization patterns; and the [Karandaaz Financial Inclusion Survey (K-FIS) 2024](https://portal.karandaaz.com.pk){:target="\_blank"}, providing granular trust metrics, financial inclusion rates, gender disaggregation, regional variation data, and documented reasons for financial exclusion. The India comparison uses [National Payments Corporation of India (NPCI) UPI statistics](https://www.npci.org.in/what-we-do/upi/upi-ecosystem-statistics){:target="\_blank"} from 2016 to 2025 and regulatory policy documentation from the Reserve Bank of India. The Kenya comparison relies primarily on Jack and Suri (2014), Central Bank of Kenya annual reports, and World Bank Findex data.

The selection of Pakistan, India, and Kenya is methodologically deliberate. All three economies deployed instant payment systems at different historical points. India's UPI (launched April 2016) is now 10 years operational. Kenya's M-Pesa (launched March 2007) is now 19 years operational. Pakistan's Raast (launched January 2021) is currently at year 5. Comparing Pakistan at year 5 with India at year 5 (2021) and Kenya at year 5 (2012) controls for system maturity and isolates behavioral variables that explain divergent outcomes. This eliminates time-of-adoption effects and focuses analysis on structural behavioral differences.

The analytical framework structures the demand-side barriers into three layers: trust deficit, incentive misalignment, and literacy friction. These layers were derived inductively from the K-FIS 2024 data on reasons for financial exclusion and reasons for non-adoption among account holders, and subsequently validated against the theoretical frameworks described in the literature review. The three barriers are conceptualized as compounding rather than substituting for each other: a person who distrusts banks, has no economic incentive to switch from cash, and cannot navigate a digital interface faces all three barriers simultaneously, creating a multiplicative rather than additive adoption barrier.

---

## 4. Pakistan's Digital Payment Landscape

Pakistan's payment infrastructure has transformed dramatically in five years. Raast, launched in January 2021 as the country's first instant payment system, processed 1,276 million peer-to-peer transactions worth PKR 29.6 trillion in FY25, compared to 147.2 million transactions worth PKR 3.1 trillion in FY23 ([State Bank of Pakistan, 2025](https://www.sbp.org.pk/PS/PDF/Annual-Payment-Systems-Review-FY25.pdf){:target="\_blank"}). This represents 8.7x growth in transaction volume over two years. The branchless banking agent network expanded to 731,814 agents, providing physical access points for account holders throughout the country. POS terminals reached 195,849 across 159,284 merchants, a 56% increase from the prior year. QR-enabled merchants doubled from 516,317 to 1,092,004. Mobile banking app users grew from 18.7 million to 24.1 million. Branchless banking mobile app users reached 79.2 million, up from 58.7 million, representing 35% growth.

The digital share of retail transactions climbed steadily from 78% in FY23 to 85% in FY24 to 88% in FY25 by transaction volume ([State Bank of Pakistan, 2025](https://www.sbp.org.pk/PS/PDF/Annual-Payment-Systems-Review-FY25.pdf){:target="\_blank"}). Total retail payment transactions reached 9.1 billion annually, valued at PKR 612 trillion cumulatively. Mobile banking applications alone processed 6.2 billion transactions, growing 52% year over year, representing the fastest-growing transaction channel.

These numbers unambiguously establish that infrastructure is not the bottleneck in Pakistan's payment ecosystem. The rails exist. The merchants are onboarded. The apps are downloaded and actively used. The question is therefore not why infrastructure is absent but why this infrastructure produces a cash-dominant economy rather than a digitally transacting one.

The answer begins with a critical distinction that headline numbers obscure: the 88% digital share is by transaction volume, not by transaction value. By value, the digital share is approximately 29% ([State Bank of Pakistan Q2 FY25 quarterly data](https://www.sbp.org.pk/psd/pdf/PS-Review-Q2FY25.pdf){:target="\_blank"}). High-volume, low-value digital transactions (peer-to-peer transfers, airtime top-ups, utility bill payments) inflate the volume share while cash continues to dominate high-value economic activity (retail commerce, wholesale trade, real estate transactions, informal market transactions). The 98% ATM cash withdrawal rate confirms this pattern: people use digital channels for transfers and bill payments but withdraw cash for actual spending. This reveals that digital infrastructure carries small-value, low-friction transactions while cash carries the economically significant transactions.

| Metric                           | Pakistan (Year 5) | India (Year 5)  | Kenya (Year 5)    |
| -------------------------------- | ----------------- | --------------- | ----------------- |
| System Launch                    | Jan 2021 (Raast)  | Apr 2016 (UPI)  | Mar 2007 (M-Pesa) |
| Adult Financial Inclusion        | 35%               | 77.5%           | 82%               |
| Account Ownership                | 35%               | 77.5%           | 82%               |
| Digital Payment Adoption         | 30%               | 35%             | 76%               |
| Mobile Money/Payment Account     | 30%               | 35%             | 73%               |
| Trust in Financial Institutions  | 9% (excluded)     | Higher baseline | Community-based   |
| Retail Digital Transaction Share | 88% (volume)      | 84.8% (volume)  | Merchant-driven   |
| Formal Savings Rate              | Not available     | 12%             | 27%               |
| Agent/Access Network             | 731,814           | Banking system  | 40,000+ agents    |

**Table 1. Infrastructure Comparison at Year 5 of System Launch**

---

## 5. Layer 1: Trust Deficit

The Karandaaz K-FIS 2024 provides the most granular trust data available for Pakistan's financial services sector. Among adults excluded from the formal financial system, only 9% trust banks and 8% trust mobile money providers ([Karandaaz, 2025](https://portal.karandaaz.com.pk){:target="\_blank"}). Only 36% of all adults report comfort using any financial service. These figures are not marginal variations in a generally trusting population; they describe a population-level trust deficit affecting approximately two-thirds of the adult population.

The roots of this distrust are structural and historically grounded. Pakistan's banking sector has historically served an urban, affluent minority. Branch networks concentrate in cities and metropolitan areas, leaving rural areas underserved. Account opening procedures require documentation (national identity cards, proof of address, tax identification) that many informal workers and rural populations lack. The 2008 banking crisis and periodic currency controls reinforced the perception that formal financial institutions are unreliable custodians of money. For the 85% of excluded adults who rely on family and friends for credit ([Karandaaz, 2025](https://portal.karandaaz.com.pk){:target="\_blank"}), the informal system is not a fallback option—it is the primary system, and it functions on trust relationships built through repeated interaction and social obligation that formal institutions cannot replicate in short timeframes.

Cash transactions offer anonymity and immediacy. For the estimated 40% of Pakistan's GDP that operates in the informal economy, digital transactions create a permanent record trail that many small business owners perceive as tax exposure risk. This perception is not irrational behavior or unfounded fear; it is a rational response to an incentive structure where formalization carries direct costs (documentation burdens, taxation obligations, compliance requirements) without proportionate benefits for small operators. Formalizing means higher tax liability without corresponding increase in customer demand, quality of service, or market opportunity.

The comparison with Kenya is instructive and illuminating. M-Pesa's adoption in Kenya overcame significant institutional distrust through a specific mechanism: the agent network. M-Pesa agents were existing shopkeepers embedded in local trust networks (Jack & Suri, 2014), individuals who had already established community trust through years of business operation. Users did not need to trust Safaricom (the telecom provider) or the banking system; they trusted the person behind the counter whom they had known for years. By 2012, five years after launch, Kenya had developed over 40,000 M-Pesa agents, and 42% of adults held mobile money accounts (World Bank Findex, 2011). Trust was not built through institution-building but through leveraging existing social institutions.

Pakistan's branchless banking agent network is numerically larger than Kenya's (731,814 agents by FY25 vs. Kenya's peak of 40,000), but it serves a population roughly four times Kenya's size, giving substantially lower per-capita agent density. More importantly, the agent network primarily facilitates cash-in/cash-out transactions (converting digital money back to physical cash), not digital payment facilitation. Agents are access points for the cash economy, not bridges to the digital one. Raast, meanwhile, is entirely app-based. It requires a smartphone, an internet connection, and a bank account—all of which presuppose a level of institutional engagement and technological comfort that the trust-deficit population does not possess.

India's UPI addressed the trust problem differently through architectural choice. Built on bank interoperability rather than a single provider, UPI distributed trust across the entire banking system. A user did not need to trust a new entity or a telecom company; they transacted through their existing bank via a standardized protocol. This design choice embedded familiarity into the digital experience. Pakistan's Raast operates on a similar interoperable architecture, but the underlying institutional trust is lower: only 9% of excluded Pakistanis trust banks versus India's higher institutional trust baseline, supported by the Jan Dhan Yojana program that created over 500 million bank accounts and established a direct relationship between the state and previously unbanked citizens.

---

## 6. Layer 2: Incentive Misalignment

The 98% ATM cash withdrawal rate is the single most revealing statistic in Pakistan's payment data ([State Bank of Pakistan, 2025](https://www.sbp.org.pk/PS/PDF/Annual-Payment-Systems-Review-FY25.pdf){:target="\_blank"}). It means that even people who have bank accounts and debit cards, who have already overcome the trust barrier sufficiently to maintain formal financial relationships, still choose to convert digital money to physical cash before spending it. This is a revealed preference in the economic sense, and it points unambiguously to an incentive structure that actively favors cash over digital spending.

For merchants, the incentive calculus is explicit and transparent. Accepting digital payments means paying merchant discount rate (MDR) fees, typically 1.5% to 2.5% of transaction value. For a small retailer operating on thin profit margins (often 5–15% on retail goods), this is a direct cost reduction that eliminates profitability on affected transactions. Cash carries no fee. Additionally, accepting digital payments creates a transaction trail that automatically feeds into tax reporting and formalization requirements. For businesses operating partially or fully in the informal economy, this is a cost that goes beyond the MDR itself—it is the cost of formalization, documentation, and potential increased tax liability. The rational response is to accept cash and avoid both the direct fee and the indirect formalization costs.

For consumers, the incentive to use digital payments for retail purchases is weak. Cash is universally accepted everywhere. Digital payment acceptance, despite the QR merchant expansion to over one million merchants, remains inconsistent and geographically concentrated. A consumer who attempts to pay digitally and encounters a merchant who prefers cash faces social friction (explaining why they cannot pay cash), time cost (navigating refusal and alternative payment methods), and uncertainty (will the transaction succeed?). The path of least resistance is cash.

The contrast with India is sharp and directly causal. In 2019, the Reserve Bank of India mandated zero MDR on all UPI transactions below Rs 2,000, covering the vast majority of retail transactions. This single policy decision removed the merchant incentive penalty entirely. Merchants faced no cost for accepting UPI, only convenience and the potential of slightly faster transaction processing. The result was explosive merchant adoption: UPI transactions grew from 8.7 billion in 2019 to 228.3 billion in 2025, with daily averages reaching 698 million in December 2025 ([NPCI, 2025](https://www.npci.org.in/what-we-do/upi/upi-ecosystem-statistics){:target="\_blank"}). This represents a 26-fold increase in transaction volume over six years following the policy change. The policy lever directly moved merchant behavior by reframing the cost-benefit calculation.

Pakistan has not implemented equivalent MDR relief. The State Bank of Pakistan has encouraged digital payment adoption through regulatory guidance and encouragement, but the cost structure remains intact. Merchants who accept Raast or card payments bear fees that cash-accepting competitors avoid. This creates an asymmetric competitive advantage for cash-accepting merchants and a systematic penalty for digital adopters.

Government-to-person (G2P) payments offer the clearest evidence that incentive design drives adoption behavior. Pakistan's BISP/Ehsaas social protection payments, delivered digitally to beneficiaries' accounts, have high adoption rates precisely because recipients have no choice: the payment arrives digitally, and accessing it requires engaging with the digital system. This is not voluntary adoption driven by perceived benefit; it is structurally induced adoption driven by incentive design. Recipients must use digital systems to access available resources. The lesson is robust: when the incentive structure changes, behavior follows predictably.

Kenya's M-Pesa demonstrates a different but complementary incentive mechanism. Agent commissions created a positive economic incentive for agents to promote mobile money usage and to encourage customers to conduct digital transactions. Agents earned revenue by facilitating transactions, aligning their economic interest with adoption growth. Pakistan's branchless banking agents operate on a similar commission model, but the commission structure incentivizes cash-in/cash-out transactions rather than sustained digital payments. The agent's economic incentive is to keep users cycling through cash, maintaining cash intermediation, rather than to move them permanently into digital channels.

---

## 7. Layer 3: Literacy Friction

The third layer compounds the first two barriers multiplicatively. Even users who trust digital systems sufficiently to attempt adoption and who have economic incentives to use them face friction from interfaces that assume digital literacy, technology familiarity, and English language proficiency.

Pakistan's smartphone penetration has grown rapidly and impressively. However, smartphone ownership does not equal digital literacy or financial service literacy. The K-FIS 2024 data shows a significant urban-rural gap in digital financial services usage even at equal infrastructure access levels ([Karandaaz, 2025](https://portal.karandaaz.com.pk){:target="\_blank"}). In urban areas with comparable smartphone penetration and network coverage to rural areas, digital financial services usage rates are substantially higher than in rural areas. This gap cannot be explained by infrastructure alone; it reflects literacy friction—the difficulty users face in navigating interfaces designed by and for digitally literate populations.

The specific manifestations of literacy friction in Pakistan are well-documented. Urdu language user interfaces for banking apps and payment services are frequently poor direct translations of English-language originals, with unintuitive navigation flows and technical terminology that assumes prior financial literacy and familiarity with banking concepts. USSD-based services (Unstructured Supplementary Service Data, a protocol allowing text-based transactions on basic phones), which could serve feature phone users and reduce interface friction, have complex multi-step menu trees that require memorization and multiple interactions to complete transactions. IVR-based services (Interactive Voice Response, a voice-guided telephone system), which offer another pathway, are similarly underutilized. Biometric verification systems, mandated for regulatory compliance in many financial services, fail for manual laborers whose fingerprints are worn or damaged from physical work, creating a physical barrier to a digital process. Elderly users or users with limited formal education struggle with abstract interface concepts.

Phone ownership itself reveals a gender dimension to literacy friction. According to K-FIS 2024, 82% of men own phones compared to 46% of women ([Karandaaz, 2025](https://portal.karandaaz.com.pk){:target="\_blank"}). Account ownership reflects this gap: 56% of men versus 14% of women hold financial accounts. Digital financial inclusion is not merely a technology problem; it is a gender equity problem with technology as the mediating channel. Women's lower phone ownership reflects both income constraints and control dynamics within households. Even where women do own phones, lower education levels on average translate to lower digital literacy, creating a compounding barrier.

India addressed literacy friction through deliberate product design choices at the system level. The BHIM (Bharat Interface for Money) app, launched in 2017, was designed explicitly for simplicity rather than feature richness and was available in 13 regional languages rather than English and Hindi only. UPI 123PAY, introduced in 2022, enabled UPI transactions on feature phones via interactive voice response (IVR), extended access via proximity-based NFC (near-field communication), and enabled transactions initiated via missed calls. These interventions did not solve literacy friction completely, but they demonstrated systematically that product design choices can materially reduce friction for populations with lower digital literacy.

Pakistan's Raast ecosystem has not yet implemented equivalent accessibility measures. The system is smartphone-dependent, app-based, and designed primarily for digitally literate users with English language proficiency or strong Urdu education. Feature phone users, Urdu-primary speakers, and users with low digital literacy are structurally excluded not by infrastructure absence but by design assumptions embedded in the system.

| Barrier                    | Pakistan                               | India                                        | Kenya                              |
| -------------------------- | -------------------------------------- | -------------------------------------------- | ---------------------------------- |
| **Trust Deficit**          | 9% of excluded trust banks             | Jan Dhan created institutional relationship  | Agent network = community trust    |
| **Incentive Misalignment** | Merchants pay 1.5-2.5% MDR             | Zero MDR policy (2019) removed penalty       | Agent commission aligns incentives |
| **Literacy Friction**      | Urdu interfaces poor, USSD/IVR minimal | BHIM: 13 languages, 123PAY on feature phones | Limited digital literacy demands   |
| **Stage at Year 5**        | Adoption plateau                       | Inflection point (UPI growth accelerates)    | Sustained adoption (82% by 2021)   |

**Table 2. Behavioral Barrier Comparison: Pakistan vs. India vs. Kenya**

---

## 8. Discussion

The three layers of the behavioral last mile are not independent variables that can be addressed sequentially; they compound multiplicatively and interact with each other in ways that create exponentially higher barriers to adoption. A consumer who distrusts banks is unlikely to be convinced to overcome that distrust by an app with poor interface usability and lack of customer support. A merchant facing 2.5% discount fees that directly reduce profits will not accept digital payments simply because the interface is well-designed in Urdu. A user with low digital literacy will not adopt digital payments solely on the basis that they have economic incentives, if the interface requires multiple steps and assumes technical knowledge. These barriers are multiplicative, not additive: overcoming one barrier only becomes valuable when others are addressed simultaneously.

The comparative analysis with India and Kenya reveals that structural solutions exist for each barrier and that policy intervention in the early years of system deployment is far more effective than attempting to retrofit adoption mechanisms later. India's policy intervention on MDR demonstrates empirically that removing merchant incentive friction accelerates adoption exponentially and sustainably: UPI transactions grew 26-fold in six years after the zero MDR policy was implemented. This growth was not a temporary surge but a sustained change in merchant and consumer behavior patterns. Kenya's agent network demonstrates that trust barriers can be bridged effectively through existing social institutions and pre-existing trust relationships rather than requiring populations to establish new institutional relationships from scratch.

Pakistan's current regulatory strategy emphasizes supply-side infrastructure deployment: building more payment terminals, onboarding more merchants onto digital acceptance, expanding agent networks, and improving network coverage. These interventions are necessary for digital payment system viability but are manifestly insufficient for achieving behavioral adoption at population scale. Five years after Raast launch, with 88% digital transaction volume by channel, 731,814 agents deployed, one million QR code merchants onboarded, and comprehensive mobile banking infrastructure, the behavioral last mile remains largely unchanged. The 98% ATM cash withdrawal rate and 60% cash dominance in economic activity suggest that the infrastructure is sufficient; the demand-side behavioral barriers are not being addressed.

The policy window for intervention is narrowing rapidly. As digital infrastructure approaches saturation in urban areas and affluent populations, the remaining adoption barriers become increasingly concentrated in populations with the deepest trust deficits, the weakest incentive alignment (the populations most dependent on informal economy), and the lowest digital literacy: the rural poor, informal economy workers, and women. These populations cannot be reached through further infrastructure investment alone. The marginal return on additional infrastructure investment is declining while behavioral barriers remain unaddressed.

Moreover, the precedents from India and Kenya suggest that early intervention in system design and policy is more cost-effective than retrofitting adoption mechanisms later in system maturity. India's zero MDR policy, implemented in the second year of UPI deployment, leveraged the system's nascent infrastructure to reorient merchant incentives before alternative payment channels became entrenched and behavioral norms around digital adoption solidified. Pakistan, in year 5 of Raast operation, still has the opportunity to implement equivalent demand-side interventions, but that policy window is rapidly closing as behavioral norms around cash usage and merchant preferences for cash become increasingly entrenched.

---

## 9. Recommendations

The following five interventions are derived from the comparative analysis of Pakistan, India, and Kenya. Each addresses a specific behavioral barrier, specifies who implements it, describes the mechanism, identifies the expected effect, and provides precedent from comparable markets.

### First: Eliminate MDR on Transactions Below PKR 5,000

The State Bank of Pakistan should mandate zero merchant discount rate on all digital transactions below PKR 5,000, the threshold covering approximately 90% of retail purchase transactions. This removes the direct cost penalty that makes cash preferable for merchants from an economic standpoint.

**Implementation:** The SBP can fund this through regulatory oversight, requiring digital payment processors and card networks to absorb costs, or through modest government subsidy.

**Precedent:** The Reserve Bank of India mandated zero MDR on UPI transactions below Rs 2,000 in 2019, and this contributed directly to a 26-fold increase in UPI transaction volume between 2019 and 2025. [See NPCI statistics](https://www.npci.org.in/what-we-do/upi/upi-ecosystem-statistics){:target="\_blank"}.

**Expected Effect:** This intervention is expected to achieve accelerated merchant acceptance of Raast and QR code payment mechanisms, particularly for small-value transactions, removing the fundamental barrier preventing merchants from accepting digital payments.

### Second: Redesign Raast for Feature Phones

The State Bank of Pakistan and Raast participant banks should develop a USSD or IVR-based Raast access channel that does not require a smartphone or internet connection. This addresses the literacy friction and device access barriers simultaneously.

**Implementation:** Development of USSD menus that are substantially simpler than current banking USSD interfaces, with voice guidance options for users with low literacy. The interface should complete a transaction in fewer than four steps.

**Precedent:** India's [UPI 123PAY service](https://www.npci.org.in/what-we-do/upi/upi-ecosystem-statistics){:target="\_blank"}, introduced in 2022, enables feature phone UPI transactions via missed call, IVR, and proximity NFC mechanisms. This extension of UPI access to feature phones is a model for Pakistan to follow.

**Expected Effect:** This intervention extends Raast access substantially to the 54% of women who do not own smartphones and to rural populations with limited smartphone penetration, while reducing interface friction for users with low digital literacy.

### Third: Deploy Trust Intermediaries at the Last Mile

Rather than relying solely on app-based interfaces and institutional channels, Pakistan should substantially incentivize branchless banking agents to actively facilitate Raast peer-to-peer transactions and bill payments (not merely cash-in/cash-out transactions).

**Implementation:** Restructure agent commissions to reward digital transaction facilitation and volume over cash cycling. Provide agent training and support materials in Urdu. Allow agents to assist users with transactions at no cost, reducing literacy friction.

**Precedent:** Kenya's M-Pesa agent commission model, where agents earned revenue directly by promoting mobile money transactions and assisting users, created alignment between agent economic incentives and adoption growth. Kenya achieved 42% adult mobile money adoption at year 5 partially through this mechanism.

**Expected Effect:** This intervention reduces the institutional trust gap by embedding digital payment facilitation in existing community trust relationships. Users can access support from trusted community members rather than requiring direct engagement with unfamiliar banking institutions.

### Fourth: Create a Tax Incentive for Documented Digital Spending

The Federal Board of Revenue should offer a small tax rebate (0.5% to 1% of documented digital transaction value) on documented digital retail transactions. This directly inverts the current incentive structure, converting the perceived cost of formalization (tax exposure) into a tangible benefit (tax reduction).

**Implementation:** Integration of digital payment transaction data with tax filing systems so that documented digital spending automatically reduces tax liability. The rebate mechanism incentivizes both merchants and consumers to conduct business digitally.

**Precedent:** South Korea's tax deduction system for card payments, implemented in the early 2000s, accelerated the cash-to-card transition significantly. The tax incentive mechanism directly changed consumer and merchant behavior by making digital payment financially advantageous.

**Expected Effect:** This intervention shifts the incentive calculus for consumers and merchants who currently prefer cash to avoid tax documentation, converting documentation from perceived cost to perceived benefit.

### Fifth: Mandate Urdu-First Financial App Design Standards

The State Bank of Pakistan should issue comprehensive design guidelines requiring that all Raast-enabled banking apps meet minimum usability standards explicitly for Urdu-primary users. These standards should mandate native Urdu interfaces (not English-to-Urdu translations), simplified transaction flows requiring fewer than four steps to complete standard transactions, and voice-guided options for users with low literacy.

**Implementation:** Regulatory requirement and auditing for compliance. Provision of design templates and resources to banks and fintech providers.

**Precedent:** India's design standards for the BHIM app and recommendations for regional language implementation across UPI-enabled applications. India's emphasis on regional language support and simplicity-first design contributed to higher adoption among lower-literacy populations.

**Expected Effect:** This intervention reduces literacy friction substantially for the estimated 70% of Pakistan's population whose primary language is Urdu rather than English, materially lowering adoption barriers for rural and lower-literacy populations.

---

## 10. Conclusion

Pakistan's digital payment infrastructure is not failing. By transaction volume metrics, it is succeeding: 88% digital transaction share in retail payments, 8.7x Raast growth over three years, one million merchants accepting QR code payments, and billions of mobile banking transactions annually. The failure is not in infrastructure but in the foundational assumption that infrastructure deployment produces behavioral change. It demonstrably does not. The behavioral last mile—the compounding barriers of trust deficit, incentive misalignment, and literacy friction—explains why a country with scaled digital payment rails and extensive infrastructure still operates as a predominantly cash economy in economic value terms.

India's UPI system succeeded not because the technology was superior to Raast—the systems are architecturally similar—but because policy design deliberately addressed each of these behavioral barriers: zero MDR removed the merchant cost penalty, Jan Dhan Yojana created the account base and established state-backed institutional relationships, BHIM reduced literacy friction through simplicity and regional language support, and demonetization (2016) provided an unrepeatable behavioral shock that accelerated adoption. Kenya's M-Pesa succeeded because it solved a specific, acute pain point (domestic remittances faced extreme costs) through a trust mechanism (agents embedded in existing communities) that did not require institutional credibility or technology literacy.

Pakistan has not yet found its equivalent catalytic use case or behavioral design strategy. Raast is architecturally sound and operationally functional but behaviorally incomplete. The five interventions proposed in this paper target the specific demand-side barriers that infrastructure deployment alone cannot resolve. Infrastructure is necessary for payment system digitalization. It is not sufficient. The behavioral last mile requires deliberate behavioral design, not just infrastructure deployment. The policy window for implementing these interventions remains open but is narrowing as behavioral norms around cash usage become entrenched and as populations outside urban, affluent centers become increasingly marginalized by infrastructure-only strategies.

---

## Data Availability Statement

All data derived from publicly available sources. URLs and permanent links provided in references section.

## Author Contributions

**Fawad Liaqat:** Conceptualization, Data Curation, Formal Analysis, Writing - Original Draft, Writing - Review and Editing.

## Conflict of Interest

The author declares no conflict of interest.

---

## References

[Central Bank of Kenya. (2012). Annual Report 2012. Nairobi: Central Bank of Kenya.](https://www.centralbank.go.ke/uploads/550643262_2012%20Annual%20Report.pdf){:target="\_blank"}

Davis, F. D. (1989). [Perceived usefulness, perceived ease of use, and user acceptance of information technology](https://misq.umn.edu/misq/article-abstract/13/3/319/191/Perceived-Usefulness-Perceived-Ease-of-Use-and){:target="\_blank"}. _MIS Quarterly_, 13(3), 319–340. https://doi.org/10.2307/249008

Demirguc-Kunt, A., Klapper, L., Singer, D., & Ansar, S. (2022). [The Global Findex Database 2021: Financial Inclusion, Digital Payments, and Resilience in the Age of COVID-19](https://documents.worldbank.org/en/publication/documents-reports/documentdetail/099818107072234182){:target="\_blank"}. Washington, DC: World Bank. https://doi.org/10.1596/978-1-4648-1897-4

Gefen, D., Karahanna, E., & Straub, D. W. (2003). [Trust and TAM in online shopping: An integrated model](https://aisel.aisnet.org/misq/vol27/iss1/4/){:target="\_blank"}. _MIS Quarterly_, 27(1), 51–90. https://doi.org/10.2307/30036519

Jack, W., & Suri, T. (2014). [Risk sharing and transactions costs: Evidence from Kenya's mobile money revolution](https://www.aeaweb.org/articles?id=10.1257/aer.104.1.183){:target="\_blank"}. _American Economic Review_, 104(1), 183–223. https://doi.org/10.1257/aer.104.1.183

Kahneman, D., & Tversky, A. (1979). [Prospect theory: An analysis of decision under risk](https://www.econometricsociety.org/publications/econometrica/1979/03/01/prospect-theory-analysis-decision-under-risk){:target="\_blank"}. _Econometrica_, 47(2), 263–292. https://doi.org/10.2307/1914185

Karandaaz Pakistan. (2025). [Pakistan Financial Inclusion Survey (K-FIS) 2024](https://portal.karandaaz.com.pk){:target="\_blank"}. Islamabad: Karandaaz Pakistan.

National Payments Corporation of India. (2025). [UPI Ecosystem Statistics: December 2025](https://www.npci.org.in/what-we-do/upi/upi-ecosystem-statistics){:target="\_blank"}. Mumbai: NPCI.

Reserve Bank of India. (2019). Notification on Charges and MDR for Digital Payments. Mumbai: RBI.

Rogers, E. M. (2003). _Diffusion of Innovations_ (5th ed.). New York: Free Press.

State Bank of Pakistan. (2025). [Annual Payment Systems Review FY25](https://www.sbp.org.pk/PS/PDF/Annual-Payment-Systems-Review-FY25.pdf){:target="\_blank"}. Karachi: SBP.

State Bank of Pakistan. (2025). [Quarterly Payment Systems Review Q2 FY25](https://www.sbp.org.pk/psd/pdf/PS-Review-Q2FY25.pdf){:target="\_blank"}. Karachi: SBP.

World Bank. (2011). Global Findex Database 2011. Washington, DC: World Bank.

World Bank. (2025). [Global Findex Database 2025](https://www.worldbank.org/en/publication/globalfindex){:target="\_blank"}. Washington, DC: World Bank.

Zucker, L. G. (1986). Production of trust: Institutional sources of economic structure, 1840–1920. _Research in Organizational Behavior_, 8, 53–111.

---
