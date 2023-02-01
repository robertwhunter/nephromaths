# Water and sodium

## Total body water

Sometimes it is helpful to estimate total body water.  (For example, this is a prerequisite to calculating water excess \@ref(eq:aqxs) in hyponatraemia or water deficit in hypernatraemia \@ref(eq:aqdef).)

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{total body water, }TBW = \text{body weight}\times k
  (\#eq:TBW)
\end{equation}

where k= 0.6 in men; 0.5 in women, elderly men or obesity and 0.45 in elderly women.  

An appropriate value for k - taking into account sex and body habitus - should be estimated, bearing in mind that muscle is ~70% water and adipose tissue is ~10% water.  
</div>\EndKnitrBlock{eqnpanel}

## Plasma sodium

Na^+^ is the dominant extracellular cation and, as such, its concentration depends on the total body stores of water and exchangeable ions.  Na^+^ and K^+^ are the most abundant cations (and will be accompanied by anions to maintain electroneutrality), thus:

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">The Edelman equation:  
\begin{equation}
  P_{Na} = \frac{Na_{e} + K_{e}}{TBW}
  (\#eq:edelman)
\end{equation}

...where Na~(e)~ and K~(e)~ are exchangeable sodium and potassium and TBW is total body water.  For an elegant discussion of the derivation of this equation see [@rose1986].
</div>\EndKnitrBlock{eqnpanel}

Any abnormality in plasma sodium concentration (P~Na~) usually reflects a problem with water homeostasis.  Hyponatraemia = over-hydration; hypernatraemia = dehydration.  

The role of potassium is often under-appreciated. Depletion of total body potassium (e.g. after vomiting, diarrhoea or diuretic use) can result in hyponatraemia; replenishing K^+^ stores can help to correct this [@rose1986].  

Plasma tonicity is regulated through a negative-feedback loop, with renal free-water excretion as the effector arm:  

![](figures/Na_loop.png)


## Renal water excretion

The kidneys are able to respond to purturbations in water balance by generating a dilute or a concentrated urine, varying U~Osm~ in the range 50 - 900 mOsm/kg [@lote2012a].  

Production of a `dilute urine` (i.e. excretion of free water) relies on three processes:  

1. glomerular filtration (of water and solute)  
2. generation of lumenal free water in the water-impermeable diluting segment (thick ascending loop of Henle and distal convoluted tubule)  
3. excretion of free water in water-impermeable collecting ducts in the absence of anti-diuretic hormone (ADH)  

<br>

Production of a `concentrated` urine (i.e. retention of free water) relies on:  

1. the generation of a concentrated inner medulla (due to the action of countercurrent multiplier in the loop of Henle and urea recycling);  
2. the reabsorption of water from the collecting ducts in the presence of ADH  

<br>
<br>

The range over which the kidneys can vary U~Osm~ may be limited by anything that can limit these processes (e.g. chronic renal insufficiency, diuretics, unregulated ADH secretion).  The ability of the kidneys to excrete free water is determined by U~Osm~ and by the total osmolar content of the urine, as we shall see \@ref(eq:UOsm1).  A large osmolar load will drive a solute diuresis; a low amount of filtered solute will limit water excretion.  


## Urine osmolality {#UOsm}

When an `osmolar load` (OL) is excreted in a discrete `volume` of urine (V), those two variables will determine the urine `osmolality` (U~Osm~):

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{urine osmolality, } U_{Osm} = \frac{OL}{V}
    (\#eq:UOsm1)
\end{equation}

which, when re-arranged becomes:

\begin{equation}
  \text{urine volume, } V = \frac{OL}{U_{Osm}}
    (\#eq:UOsm2)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

The reciprocal relationship between V and U~Osm~ means that the maximum urine volume used to excrete an osmolar load is determined by the lowest achievable urine osmolality in diuresis (and the minimum urine volume by the maximum possible urine osmolality in antidiuresis):

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{maximum urine volume, } V_{max} = \frac{OL}{U_{Osm_{min}}}
    (\#eq:UOsmmin)
\end{equation}

\begin{equation}
  \text{minimum urine volume, } V_{min} = \frac{OL}{U_{Osm_{max}}}
  (\#eq:UOsmmax)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

These simple relationships can be used to explore a number of phenomena, such as:  

+ explaining why drinking seawater causes dehydration  
+ explaining why giving 0.9% NaCl can exacerbate hyponatraemia in some circumstances  
+ calculating the water intake that would cause hyponatraemia  
+ explaining why poor diet (low dietary solute intake) can cause hyponatraemia    

These are considered in more detail in [this blog post](https://www.kidneyfish.net/post/e-mc-2). 


## Hyponatraemia

Hyponatraemia is caused by free water excess.  When this is associated with reduced plasma tonicity, this can cause cerebral oedema.  

The general approach to diagnosis is as follows: 

\BeginKnitrBlock{algpanel}<div class="algpanel">**Order of operations in hyponatraemia:**  
  
1. confirm true hypotonic hyponatraemia
    + correct for [glucose] in hyperglycaemia
    + check P~Osm~
2. determine clinical volume status  
3. check U~Osm~ (< 100 mM suggests urine water excretion limited by low solute load or driven by XS water intake - i.e. hypothalamic-ADH-kidney axis intact)  
4. check U~Na~ (< 30 mM suggests low effective arterial blood volume)  


And remember to consider:  

+ is there total body K depletion?
+ is solute intake low?
+ check U~K~ or calculate free water clearance to guide therapy
+ calculate FE~urate~ in tricky cases  
</div>\EndKnitrBlock{algpanel}

The causes of hyponatraemia can be classified by volume status, U~Osm~ and U~Na~:

![](figures/Na_loop_annotated.png)

### Drug causes of hyponatraemia

![](figures/HypoNa_drugs.png)



### Correction for hyperglycaemia  
Hyponatraemia can result from an influx of water into the vascular (and interstitial) space in presence of an abnormaly high concentration of a plasma osmole.  The commonest such clinical scenario is that of hyperglycaemia.  (Hyponatraemia in this context is not dangerous *per se* because plasma tonicity is maintained near normal by glucose, an [effective osmole](#tonicity).)  
<br>
<br>

The value that P~Na~ will correct to with resolution of hyperglycaemia can be estimated: 

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{corrected } P_{Na}, cP_{Na} = P_{Na}+2.4 \times \frac{P_{glucose}-5.5\text{mM}}{\text{5.5mM}}
  (\#eq:gluccorr)
\end{equation}
    
NB alternatively this can calculated by adding 0.4 mM to measured P~Na~ for every 1 mM rise in P~glucose~.  The correction factor for haemodialysis patients is lower (0.27 mM for every 1 mM glucose) [@penne2010].  
</div>\EndKnitrBlock{eqnpanel}

### Urine sodium  

In the steady-state, urinary sodium excretion will reflect sodium intake.  On a normal Western diet, daily NaCl intake might be ~9g (=154 mmoles) [@campbell2015].  If this were excreted in 2L or urine, then U~Na~ would be ~ 77mM.  
<br>
<br>

When volume homeostasis is threatened and the renin-angiotensin-aldosterone system is activated, renal sodium reabsorption is stimulated and U~Na~ drops.  As a rule-of-thumb, U~Na~ is < 30 mM in volume depletion:  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  U_{Na}<30\text{mM }=\text{low effective artieral blood volume}
  (\#eq:UNavolumestatus)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

This threshold was derived in an elegant study of patients with hyponatraemia in which *bona fide* volume depletion was determined retrospectively by a positive response to a crystalloid bolus [@chung1987].  It is more accurate to say that low U~Na~ refects low effective arterial blood volume (EABV) rather than volume depletion *per se*).  This hypothetical concept encompasses both intravascular volume and vascular tone, and is useful in explaining why the RAAS is activated in hypervolaemic (but low-perfusion) states such as heart failure and cirrhosis.    
<br>

U~Na~ will not accurately report EABV in the presence of any drug or disease that perturbs renal sodium excretion, such as:  

+ diuretics  
+ ATN  
+ salt-wasting nephropathies (Addison's, Barrter, Gitelman)  
+ bicarbonaturia (look for low U~Cl~)  
+ glycosuria  


#### FE~Na~

Urine sodium levels can be expressed as a fractional excretion.  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{fractional excretion, }FE_{Na} = \frac{U_{Na}}{P_{Na}} \times \frac{P_{Creat}}{U_{Creat}}
  (\#eq:FENa)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

Historically, FE~Na~ was used in an attempt to discriminate between an appropriate response to volume depletion in "pre-renal" AKI (FE~Na~ \< 1%) and in-appropriate salt wasting in ATN (FE~Na~ \> 3%).  However, the sensitivity and specificity of FE~Na~ in this context are poor [@pahwa2016].  (FE~urea~ can be used in a similar way and is less sensitive to error in patients who are treated with diuretics; FE~urea~ \< 35% is compatible with pre-renal AKI.)

FE~Na~ may be more useful in identifying patients exhibiting hepato-renal physiology (in which FE~Na~ << 1% and U~Na~ < 10 mM).  


### FE~urate~ as an alternative index of volume status

Urate transport in PCT is coupled to sodium transport [@kahn1989].  Volume depletion will stimulate Na reabsorption in PCT and hence also urate reabsorption.  

Interpretation[@maesaka2014; @choi2018]:  

- in normal subjects, FE~urate~ is 4 -- 11%  
- in volume depletion (or states of low EABV), FE~urate~ is low (< 4%)  
- in volume expansion, SiADH or renal salt wasting, FE~urate~ is high (> 11%)  


## Free water clearance

### Calculating free water clearance

The quantitative contribution of the kidney to water homeostasis can be determined by calculating the osmolar- or electrolyte-free water clearance.  

A dilute urine can be thought of as comprising a volume of urine that is isotonic with plasma PLUS a volume of "free" water.  A concentrated urine can be thought of as a volume of isotonic urine MINUS a volume of "free" water.  `Free water clearance` is a hypothetical concept that determines this volume of "free" water in the urine.  

Traditionally, this was calculated by first determinine the total clearance of osmoles and subtracting this from urine flow: 


\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{osmolar clearance, }C_{Osm} = \frac{U_{Osm} \times V}{P_{Osm}}
  (\#eq:COsm)
\end{equation}

\begin{equation}
  \text{free water clearance, }C_{H_{2}O} = V-C_{Osm}=V \times(1-\frac{U_{Osm}}{P_{Osm}})=\frac{OL}{U_{Osm}}\times(1-\frac{U_{Osm}}{P_{Osm}})
  (\#eq:CFW)
\end{equation}

\begin{equation}
  \text{free water reabsorption, }T^{C}_{H_{2}O} = C_{Osm}-V 
  (\#eq:RFW)
\end{equation}
</div>\EndKnitrBlock{eqnpanel}

However, as not all urinary osmoles are [*effective* osmoles](#tonicity) with respect to cell membranes, it makes more sense to determine the clearance of water that is free from only effective osmoles when working out how renal water clearance is likely to affect P~Na~.  Therefore, it is usually preferable to calculate `electrolyte-free` water clearance [@nguyen2006a].  This approach was originally advocated by [Goldberg, 1981](https://pubmed.ncbi.nlm.nih.gov/7230957/) and then elaborated on by [Rose, 1986](https://pubmed.ncbi.nlm.nih.gov/3799631/):

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{electrolyte-free water clearance, }C_{H_{2}O}(e) = V\times(1-\frac{U_{Na}+U_{K}+U_{OEOs}}{P_{Na}+P_{OEOs}})\\ \approx\frac{OL}{U_{Osm}}\times(1-\frac{U_{Na}+U_{K}}{P_{Na}})
  (\#eq:CFWE)
\end{equation}

Other effective osmoles (OEOs) may be: glucose, mannitol...
</div>\EndKnitrBlock{eqnpanel}

Most of the time, this can be simplified by considering only the dominiant urinary cations, sodium and potassium - or even further by calculating the `urine:plasma electrolyte ratio`, as proposed by [Furst, 2000](https://pubmed.ncbi.nlm.nih.gov/10768609/):  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{electrolyte clearance, }C_{El} = \frac{U_{Na+K}\times V}{P_{Na}}
  (\#eq:CEl)
\end{equation}

\begin{equation}
  \text{urine:plasma electrolyte ratio, U:P(e)} = \frac{U_{Na}+U_{K}}{P_{Na}}
  (\#eq:UPratio)
\end{equation}
</div>\EndKnitrBlock{eqnpanel}

### Clinical utility of free water clearance

The main clinical application of free water clearance is in determinine the quantitative contribution of the kidneys to the pathogenesis of hyponatraemia.  This can help if diagnosing the *cause* of hyponatraemia and in guiding *rational therapy*.  

Hyponatraemia will ensue when free water intake exceed free water clearance.  A low free water clearance, in the context of hyponatraemia, indicates some sort of problem with the ADH-kidney axis. 

Free water clearance can be used to determine the extent to which water intake should be restricted (in cases of euvolaemia or volume-expanded hyponatraemia where this should help to correct hyponatraemia).  A meticulous approach entails calculating $C_{H_{2}O}(e)$ and using this to set a value for the daily water intake that would result in hyponatraemia - accounting for any insensible water losses and obligate free water intake.  

A more straightforward approach - and one that can be followed when urine flow rate has not been documented - is to approximate $C_{H_{2}O}(e)$ from the urine:plasma electrolyte ratio \@ref(eq:UPratio) - sometimes known as the "Furst ratio" [@furst2000].  The Furst formula makes various assumptions about body size, cation intake and insensible water losses in order to give a very approximate estimate of urinary free water excretion.  

The estimates for net free water loss (and the restriction on water intake that would be required to raise plasma sodium) are as follows, with the duration being that required for 1L of urine output: 

+----------------------+-------------------------------+-------------------+
|U:P electrolyte ratio | estimated net free water loss | max fluid intake  |
+======================+===============================+===================+
| \>1.0                | 800 ml                        | 0 ml              |
+----------------------+-------------------------------+-------------------+
| 0.5 -- 1.0           | 800 - 1300 ml                 | 500 ml            |
+----------------------+-------------------------------+-------------------+
| \<0.5                | 1300 - 1800 ml                | 1000 ml           |
+----------------------+-------------------------------+-------------------+

<br>
<br>

Based on this, a popular approximate guide to fluid restriction is:  

+----------------------+----------------------------------------------------+
|U:P electrolytes      | set fluid restriction to...                        |
+======================+====================================================+
| UNa + UK \> PNa      | 500 ml (and give furosemide +/- supplemental NaCl) |
+----------------------+----------------------------------------------------+
| UNa + UK \~ PNa      | 500 - 800 ml                                       |
+----------------------+----------------------------------------------------+
| UNa + UK \< PNa      | \>1000 ml                                          |
+----------------------+----------------------------------------------------+

<br>

### Urine flow rate in hyponatraemia

Patients with hypovolaemic hyponatraemia are at particular risk of "over-correction" - i.e. a rapid rise in P~Na~ that might precipitate osmotic demyelination.  This is because after the initial phases of volume resuscitation, the volume stimulus to ADH secretion is removed and there is then a profound osmotic stimulus suppressing ADH production.  

The first clinical sign that over-correction is imminent is a rise in urine output.  But how much urine is too much urine?  Using some complicated mathematics and reasonable assumptions, [Buchkremer et al.](https://pubmed.ncbi.nlm.nih.gov/30122547/) used the Edelman equation to derive an estimate for this:  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{safe upper limit for urine flow ,}V_{safe} = 1 \text{ ml per kg BW per hr}
  (\#eq:unsafe_uo_hypoNa)
\end{equation}
    
...up to a maximum of 100 ml per hr
</div>\EndKnitrBlock{eqnpanel}

<br>

### Drug causes of hyponatraemia

<table>
<tbody>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> Mechanism </td>
   <td style="text-align:left;"> Drugs </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> Impaired urinary dilution </td>
   <td style="text-align:left;"> thiazide diuretics </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> Renal salt wasting </td>
   <td style="text-align:left;"> NSAIDs / antibiotics / PPIs (if AIN) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> SIADH </td>
   <td style="text-align:left;"> antidepressants (SSRIs, TCAs) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> SIADH </td>
   <td style="text-align:left;"> antipsychotics </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> SIADH </td>
   <td style="text-align:left;"> anticonvulsants (esp. carbemazepine) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> SIADH </td>
   <td style="text-align:left;"> anti-cancer (vinscritine, cisplatin…) </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> SIADH </td>
   <td style="text-align:left;"> opioids </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> SIADH </td>
   <td style="text-align:left;"> MDMA </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> Reset osmostat </td>
   <td style="text-align:left;"> venlafaxine </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> Reset osmostat </td>
   <td style="text-align:left;"> carbamazepine </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;background-color: white !important;"> Excessive thirst </td>
   <td style="text-align:left;"> MDMA </td>
  </tr>
</tbody>
</table>



## Hypernatraemia

In contrast to hyponatraemia, which may pose a diagnostic conundrum, in hypernatraemia it is almost always easy to work out the underlying cause.  Hypernatraemia is caused by loss of free water (dehydration).  Because the thirst resoponse is such a powerful negative feedback controlled of P~Osm~, in most cases hypernatraemia arises through *lack of access to water* rather than excessive water losses *per se*.  This is often iatrogenic: a classic example being the patient with chronic diabetes insipidus who, having been used to drinking many litres of water per day, becomes hypernatraemic when they are admitted to hospital and their access to water is limited.  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}

  \text{water excess } = TBW \times (1-\frac{P_{Na}}{140})
  (\#eq:aqxs)
\end{equation}</div>\EndKnitrBlock{eqnpanel}


The treatment of hypernatraemia is simple: give more free water (either enterally or as intravenous 5% glucose).  The total body water deficit can be estimated as follows (where total body water, TBW is given by \@ref(eq:TBW)):

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{water defecit } = TBW \times (\frac{P_{Na}}{140}-1)\approx \frac{P_{Na}-140}{3}
  (\#eq:aqdef)
\end{equation}
</div>\EndKnitrBlock{eqnpanel}

Armed with this estimate, fluid may be prescribed at an appropriate rate to achieve gradual restoration of normal plasma tonicity.  
