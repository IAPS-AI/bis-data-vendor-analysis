# Deep Dive: The BIS-Sayari Engagement

## Contract Timeline

| Award | Date | Amount | Description | Period |
|-------|------|--------|-------------|--------|
| **1331L521P13160034** | Feb 2021 | $80,000 | Database License Support | 1 year |
| **1331L522P13160038** | Mar 2022 | $82,800 | Licenses | 7 months |
| **1331L523P13160022** | Mar 2023 | $85,000 | Security Software Support / Sayari Data Access | 1 year |
| **1331L524C0008** | Sep 2024 | **$1,500,000** | Corporate Governance Data (Commercial Data Hub Pilot) | 18 months |

**Total BIS-Sayari Spend: ~$1.75 million**

---

## The Trajectory: From Pilot to Strategic Partnership

### Phase 1: Initial Pilot (FY2021) - $80K
The relationship began modestly in February 2021 with a single "database license support" purchase. At this point:
- Sayari was still a relatively small company (had just raised $40M Series C)
- BIS was likely testing the platform's utility for export control investigations
- The contract was a simple purchase order, not a multi-year commitment

### Phase 2: Continued Testing (FY2022-2023) - ~$168K
The next two years saw incremental renewals at similar price points ($82-85K), suggesting:
- BIS found value in the initial pilot
- But hadn't yet committed to enterprise-wide adoption
- The "Security Software Support" and "Sayari Data Access" descriptions indicate they were using Sayari Graph for investigations

**Key context:** This period coincided with the October 2022 semiconductor export controls - the most significant expansion of export restrictions on China in decades. BIS suddenly had far more entities to screen and investigate.

### Phase 3: Major Scale-Up (FY2024) - $1.5M
The September 2024 contract represents a **17x increase** over previous annual spending. Key indicators:

1. **Different contract vehicle**: Awarded through the "Commercial Data Hub Pilot Program" - a Commerce-wide initiative to acquire commercial data
2. **Different description**: "Corporate Governance Data" rather than just licenses - suggests bulk data integration
3. **Longer period**: 18 months (through March 2026)
4. **Sayari Graph explicitly named** in modification descriptions

---

## What This Tells Us

### 1. BIS is industrializing entity screening

The shift from ~$80K/year licenses to $1.5M for "corporate governance data" suggests BIS moved from:
- Individual analysts using Sayari's web interface for investigations
- To **bulk data integration** into BIS's own systems

This aligns with Sayari's BIS50 module, which pre-computes ownership chains for all Entity List companies to identify 50%-owned subsidiaries that inherit export restrictions.

### 2. The timing tracks regulatory expansion

| Date | BIS Action | Sayari Contract |
|------|------------|-----------------|
| Feb 2021 | - | First contract ($80K) |
| **Oct 2022** | **Semiconductor export controls** | - |
| Mar 2022 | - | Renewal ($83K) |
| Oct 2023 | Expanded controls, 13 entities added | - |
| Mar 2023 | - | Renewal ($85K) |
| **Dec 2024** | **140 new entities designated** | - |
| Sep 2024 | - | **Major scale-up ($1.5M)** |

The Entity List grew from ~1,350 entries in 2019 to ~3,350 by March 2025. Each entity triggers a cascade of screening requirements for their subsidiaries. Sayari's graph database automates this.

### 3. Sayari's government business was exploding simultaneously

From the TPG investment announcement:
> "In 2023, the company was awarded contracts in the U.S., UK, Canada, Australia, and the EU... the company's expansion into international governments accelerated **950% over the past year**."

Other concurrent government contracts:
- **CBP**: $7.8M contract (Nov 2022) for UFLPA/forced labor compliance
- **DEA**: Sole-source contract (2022)
- **UK Government**: Government-wide contract (Dec 2022)

---

## The Founders' Background

Farley Mesko (CEO) and Benjamin Power (COO) both came from **C4ADS**, a Google/Palantir-backed national security research organization. Mesko:
- Was COO of C4ADS (2010-2015)
- Testified before Congress on using open-source data to combat terrorist financing
- Founded Sayari in 2015 explicitly to serve government investigators

This isn't a commercial company that pivoted to government work - it was **built for this mission from day one**.

---

## What's Next?

The contract modifications through FY2026 ("PROVIDE THE FUNDING FOR THE SAYARI GRAPH REQUIREMENT") suggest this is now an ongoing operational capability, not a pilot. Given:

1. The BIS 50% rule now requires screening subsidiaries of ~3,350 entities
2. New export controls are added "at least annually" per Secretary Raimondo
3. The Commercial Data Hub is an ongoing program through 2026+

I'd expect the BIS-Sayari relationship to continue growing, potentially toward the scale of the CBP contract ($7.8M).

---

## Sources
- [Sayari Awarded Contract with U.S. Department of Commerce](https://sayari.com/resources/sayari-awarded-contract-with-us-department-of-commerce/) (July 2022)
- [TPG $235M Investment Announcement](https://www.tpg.com/news-and-insights/sayari-closes-235-million-strategic-investment-from-tpg-inclusive-of-additional-capital-for-organic-growth-and-ma)
- [Sayari BIS50 Module Launch](https://sayari.com/resources/pr-sayari-launches-bis50-signal-module-in-response-to-anticipated-u-s-export-control-expansion/)
- [Commercial Data Hub Pilot Program](https://sam.gov/opp/e526cae3596d422d89594619bfadd227/view)
- [CRS Report: U.S. Export Controls and China](https://www.congress.gov/crs-product/R48642)
- [CBP $7.8M Contract](https://www.businesswire.com/news/home/20221115005372/en/Sayari-Awarded-$7.8M-Enterprise-Trade-Analytics-Contract-to-Support-U.S.-Customs-Border-Protection)

---

## Contract Details for Citation

### Award 1: 1331L521P13160034
- **Transaction Key:** 1301_-NONE-_1331L521P13160034_0_-NONE-_0
- **Award Key:** CONT_AWD_1331L521P13160034_1301_-NONE-_-NONE-
- **Vendor UEI:** YZZ2MKYNW468
- **USAspending:** https://www.usaspending.gov/award/CONT_AWD_1331L521P13160034_1301_-NONE-_-NONE-/

### Award 2: 1331L522P13160038
- **Transaction Key:** 1301_-NONE-_1331L522P13160038_0_-NONE-_0
- **Award Key:** CONT_AWD_1331L522P13160038_1301_-NONE-_-NONE-
- **Vendor UEI:** YZZ2MKYNW468
- **USAspending:** https://www.usaspending.gov/award/CONT_AWD_1331L522P13160038_1301_-NONE-_-NONE-/

### Award 3: 1331L523P13160022
- **Transaction Key:** 1301_-NONE-_1331L523P13160022_0_-NONE-_0
- **Award Key:** CONT_AWD_1331L523P13160022_1301_-NONE-_-NONE-
- **Vendor UEI:** YZZ2MKYNW468
- **USAspending:** https://www.usaspending.gov/award/CONT_AWD_1331L523P13160022_1301_-NONE-_-NONE-/

### Award 4: 1331L524C0008
- **Transaction Key:** 1301_-NONE-_1331L524C0008_0_-NONE-_0
- **Award Key:** CONT_AWD_1331L524C0008_1301_-NONE-_-NONE-
- **Vendor UEI:** YZZ2MKYNW468
- **USAspending:** https://www.usaspending.gov/award/CONT_AWD_1331L524C0008_1301_-NONE-_-NONE-/
