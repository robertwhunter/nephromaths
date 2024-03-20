# Metabolic acidosis

### Anion & osmolar gaps

Metabolic acidoses are classified as `wide-anion-gap` (WGMA) or `normal-anion-gap` (= hyperchloraemic, HCMA).  In WGMA, the acidosis is caused by an exogenous acid present in plasma.  This is not measured directly, but will manifest as an apparent "anion gap".  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{anion gap, } AG=P_{Na}-P_{HCO_{3}}-P_{Cl}
  (\#eq:AGap)
\end{equation}

NB some people also include P~K~ in the calculation.  
    
\begin{equation}
  \text{corrected anion gap, } cAG=AG+\frac{40-P_{albumin}}{4}
  (\#eq:cAGap)
\end{equation}
    
NB ADD ON to correct for hypoalbuminaemia.  
    </div>\EndKnitrBlock{eqnpanel}

![](figures/cAG.png)

A normal AG is 12 ± 2 (or 16 ± 2 if include K^+^ in the calculation).  

'Deltas' are calculated by comparing to expected normal values (for AG or HCO~3~).  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{delta anion gap, } \Delta AG=AG-12
  (\#eq:DelAGap)
\end{equation}

\begin{equation}
  \text{delta bicarbonate, } \Delta HCO_{3}=25-P_{HCO{3}}
  (\#eq:DelHCO)
\end{equation}

\begin{equation}
  \text{delta ratio, } =\frac{\Delta AG}{\Delta HCO_{3}}
  (\#eq:DelRatio)
\end{equation}

\begin{equation}
  \text{delta delta, } \Delta \Delta = \Delta AG - \Delta HCO_{3} \text{ (in ketoacidosis)}\\
  \text{delta delta, } \Delta \Delta = (0.6 \times \Delta AG) - \Delta HCO_{3} \text{ (in lactic acidosis)}\\
  (\#eq:deltadelta)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

The correction factor (0.6) applied when computing the delta in lactic acidosis is thought to be due to lower renal clearance of lactate (compared to ketone) anions [@berend2014].  

Normal range for delta ratio (ΔAG / ΔHCO~3~) is 1 -- 2.  

Therefore to interpret delta ratios:  

![](figures/AG2.png)

`Osmolar gaps` are used to identify exogenous or un-measured osmoles in the plasma (which may be present in a subset of WGMA in which the acid is osmotically active): 

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{calculated osmolality, } cP_{Osm} =(2\times P_{Na})+P_{urea}+P_{glucose}
  (\#eq:calcOsm)
\end{equation}

\begin{equation}
  \text{osmolar gap, } OG = \text{measured } P_{Osm} - cP_{Osm}
  (\#eq:Osmgap)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

Historically, it has been technically difficult to measure urinary ammonium.  Therefore the *urinary* anion gap has been used as a proxy measure - either in isolation or in combination with the urinary osmolar gap [@kraut2012; @sharma2015]: 

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{urinary anion gap, } UAG=U_{Na}+U_{K}-U_{Cl}
  (\#eq:urineAGap)
\end{equation}

\begin{equation}
  \text{calculated urinary osmolality, } cU_{Osm} = 2 \times (U_{Na}+U_{K})+U_{urea}+U_{glucose}
  (\#eq:calcUOsm)
\end{equation}

\begin{equation}
  \text{urinary osmolar gap, } UOG=\text{measured } U_{Osm} - cU_{Osm}
  (\#eq:UOsGap)
\end{equation}

\begin{equation}
  \text{urinary cations, } U_{cations}=\frac{U_{Osm}-U_{urea}-U_{glucose}}{2}
  (\#eq:UCat)
\end{equation}

\begin{equation}
  \text{calculated urinary ammonium, } cU_{NH_{4}}\approx UAG \approx \frac{UOG}{2} \approx U_{cations}-(U_{Na}+U_{K})
  (\#eq:UCalcNH)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

UAG normal range is positive 30 -- 50.  

### Causes of a metabolic acidosis

#### Approach to metabolic acidosis


\BeginKnitrBlock{algpanel}<div class="algpanel">Order of investigations in metabolic acidosis:  

1)  cAG -- is this a normal or wide gap acidosis?
2)  ΔAG vs ΔHCO~3~ in WGMA -- is rise in AG proportional to fall in HCO~3~ (or is this a mixed metabolic disorder)?  
3)  PaCO~2~ -- is the fall in PaCO~2~ proportional to the fall in HCO~3~ (0.16 kPa per mM)?  
4)  +/- OG for a WGMA  
5)  +/- UAG for HCMA  
6)  +/- FEHCO~3~ for HCMA with --ve UAG  

ΔAG / ΔHCO~3~ \< 1 mixed WGMA / HCMA or urinary ketone losses (DKA)
ΔAG / ΔHCO~3~ \> 2 mixed WGMA and metabolic alkalosis
  </div>\EndKnitrBlock{algpanel}



#### WGMA

Differential diagnosis of a wide-gap metabolic acidosis:  

<!-- +  **G** \* glycols *ethylene glycol; propylene glycol* -->
<!-- +  **O** oxoproline -->
<!-- +  **L** L-lactate *shock, liver disease, metformin, linezolid (several weeks into Rx)* -->
<!-- +  **D** D-lactate *short bowel syndromes* -->
<!-- +  **M** \* methanol -->
<!-- +  **A** aspirin -->
<!-- +  **R** renal failure -->
<!-- +  **K** \*^?^ ketoacidosis -->

<table>
<tbody>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> G </td>
   <td style="text-align:left;"> glycols ethylene glycol; propylene glycol * </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> O </td>
   <td style="text-align:left;"> oxoproline </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> L </td>
   <td style="text-align:left;"> L-lactate shock, liver disease, metformin, linezolid (several weeks into Rx) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> D </td>
   <td style="text-align:left;"> D-lactate short bowel syndromes </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> M </td>
   <td style="text-align:left;"> methanol * </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> A </td>
   <td style="text-align:left;"> aspirin </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> R </td>
   <td style="text-align:left;"> renal failure </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> K </td>
   <td style="text-align:left;"> ketoacidosis *(?) </td>
  </tr>
</tbody>
</table>

Propylene glycol (a solvent for parenteral medications: lorazepam, diazepam, phenobarbital) is metabolised to L- and D-lactate.

\* WGMA with elevated OG = EtOH ketoacidosis, MeOH and the glycols. The OG is NOT elevated with salicylates. There is a time-dependant conversion from OG to AG following ingestion of toxic alcohol (EG > glycolic acid > oxalate). 

NB Ethylene glycol = high lactate (false +ve) on ABG machine but not formal lab assay.  

<!-- Administer fomepizole early (before significant acidosis). Indications for RRT (prefer HD to HF): acidosis, renal failure, EG level \> 50 mg/L. -->


#### HCMA (normal gap) {#HCMA}

The approach to HCMA has been extensively reviewed [@rodriguezsoriano2002; @kraut2012; @haque2012; @sharma2015).  

The causes can be classified using the urinary anion gap \@ref(eq:urineAGap) and the fractional excretion of bicarbonate \@ref(eq:FEHCO3):  

<!-- +  \+ ve U AG (unable to acidify urine) -->
<!--     +  *RTA type I (always)* -->
<!--     +  *RTA type IV (always)* -->
<!--     +  *RTA type II (sometimes) \** -->

<!-- +  -- ve U AG (able to acidify urine)   -->
<!--     +  renal (FEHCO~3~ \> 10 -- 15 %) -->
<!--         +  *RTA type II (sometimes) \** -->
<!--         +  *RTA of renal insufficiency (GFR \> 15)* -->

<!--     +  extrarenal (FEHCO~3~ \<\< 5 % \*\*)   -->
<!--         +  *diarrhoea (GI HCO~3~ loss)* -->
<!--         +  *ureteric diversion* -->
<!--         +  *pancreatic secretions* -->
<!--         +  *biliary secretions* -->

<table>
<tbody>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> POS U AG (UNABLE TO ACIDIFY URINE) </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;"> RTA </td>
   <td style="text-align:left;"> RTA type I (always) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;">  </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;"> RTA </td>
   <td style="text-align:left;"> RTA type IV (always) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;">  </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;">  </td>
   <td style="text-align:left;"> RTA type II (sometimes) * </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> NEG U AG (ABLE TO ACIDIFY URINE) </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;"> renal (FEHCO3 &gt; 10 – 15 %) </td>
   <td style="text-align:left;"> RTA type II (sometimes) * </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;">  </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;">  </td>
   <td style="text-align:left;"> RTA of renal insufficiency (GFR &gt; 15) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;">  </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;">  </td>
   <td style="text-align:left;"> diarrhoea (GI HCO3 loss) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;">  </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;">  </td>
   <td style="text-align:left;"> ureteric diversion </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;">  </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;">  </td>
   <td style="text-align:left;"> pancreatic secretions </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;">  </td>
   <td style="text-align:left;font-style: italic;background-color: white !important;">  </td>
   <td style="text-align:left;"> biliary secretions </td>
  </tr>
</tbody>
</table>

\* The UAG is positive in all distal RTA. It may be positive or negative in proximal RTA.

\*\* FEHCO~3~ also \< 5 % in dRTA.  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  FE_{HCO_{3}} = \frac{U_{HCO_{3}}}{P_{HCO_{3}}} \times \frac{P_{Creat}}{U_{Creat}}
  (\#eq:FEHCO3)
\end{equation}
    </div>\EndKnitrBlock{eqnpanel}

Hyperchloraemic acidosis may also be caused by iatrogenic `chloride excess`.  This may be particularly pronounced when IV NaCl is used to replace losses of urinary anions that represent a store of "potential bicarbonate" - e.g. ketone bodies or D-lactate [@sabatini2009].

Historically, TPN was a cause of "hyperalimentation acidosis" (as cationic amino acids were metabolised to sulphuric acid) - but contemporary formulations contain a source of potential bicarbonate (e.g. acetate) to offset this.  

HCMA in the context of urinary diverstion occurs because colonic epithelium (used to construct neo-bladder) contains a Cl/HCO~3~ exchanger.  Therefore chloride-rich urine promotes massive HCO3~3~ secretion.  Colonic epithelium is also permeable to NH~3~ so that bacterial urease activity can cause hyperammonaemic encephalopathy.  

### Cautions in the interpretation of UAG

i) extreme volume depletion 
    - results in low UNa and UCl
    - low UCl limits NH~4~ excretion and may therefore lead to a "spurious" positive UAG in diarrhoea  

ii) ketoacidosis 
    - unmeasured anions in the urine (β-hydroxybutyrate and acetoacetone)
    - may therefore lead to a positive UAG even though urinary NH4+ excretion is increased\...
    - ...detect this by measuring the urinary osmolar gap  

iii) glue-sniffing (toluene) 
    - unmeasured anions in the urine (hippurate) 

A +ve UAG in the context of *alkaline* urine could signify bicarbonaturia (post-vomiting, loop diuretics, post-hypercapnoea).
