# ICSR Processing Decision Tree

```text
Potential safety information received
                |
                v
Capture original source and receipt timestamp
                |
                v
Are all 4 minimum criteria present?
(patient + reporter + suspect product + event)
          /                 \
        No                   Yes
        |                     |
Document, seek follow-up      Valid ICSR
and assess local rules        |
                              v
                    Assign Day 0; search duplicates
                              |
                              v
                    Assess seriousness
                              |
                              v
                    Identify context and region
                      /                 \
              Post-marketing        Clinical trial
                    |                    |
                    v                    v
         Apply local ICSR rules    Assess SAE, suspected
         and reporting timelines  relationship and RSI
                    |                    |
                    |                    v
                    |             Serious + suspected +
                    |             unexpected?
                    |                /       \
                    |              Yes        No
                    |               |          |
                    |             SUSAR       Not SUSAR;
                    |             pathway    follow SAE rules
                    \_______________________________/
                                    |
                                    v
                         Code events and products
                                    |
                                    v
                    Assess severity and expectedness
                                    |
                                    v
                    Causality review (WHO-UMC/Naranjo
                    where appropriate; medical judgement)
                                    |
                                    v
                     Narrative + follow-up + QC
                                    |
                                    v
                    Submit within applicable deadline
                                    |
                                    v
                  Acknowledgement, reconciliation,
                     follow-up and case maintenance
```

A valid case may be incomplete; follow-up does not stop the clock. Seriousness, severity, expectedness and causality are separate assessments. This flowchart does not replace local legislation or SOPs.