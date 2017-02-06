<FORM><INPUT Type="button" VALUE="Back" onClick="history.go(-1);return true;"></FORM>

# Introduction to sample preparation

The microscope is not magical, without a good sample, you won't have images
 that are suitable for image analysis. Here, I just want to highlight some
important point that have to be taken into account when you prepare your sample.

***

## 1. Choice of the coverslip

In general, you should always use #1.5 coverslip (0.17mm thickness) as most
microscope objectives are designed to work optimally with these. This is true
for fixed samples as well as live samples. For live cell imaging, [Ibidi](http://ibidi.com/applications/live-cell-imaging/)
 as a very good choice of dishes and chambers.

***

## 2. Choice of your fluorophore(s)

+ First thing you should pay attention to is if you have the right laser lines and/or excitation-emission filters available, either in your lab or in the facilities around you.

+ Second, especially if you are working with living sample, try to work with fluorophores with a peak in excitation that is toward the longer wavelengths. Shorter wavelengths, such as UV, have a stronger energy and will damage your sample faster.

+ Third, obviously, you want a bright fluorophore (high quantum yield) with a long lifetime. To choose from the myriad of fluorophore, I will recommend to use the [fluorescent protein visualization](http://www.fpvis.org/) tool develop by Talley Lambert and Kurt Thorn.

+ Finally, avoid as much as possible any cross talk between your fluorophores, to check for that, you can use the [Fluorescence SpectraViewer](https://www.thermofisher.com/us/en/home/life-science/cell-analysis/labeling-chemistry/fluorescence-spectraviewer.html) from Thermo Fisher Scientific.

***

## 3. Fixation and permeabilization

Fixing and permeabilizing your cells affects the cell morphology and the availability of the antigen you are trying to detect. You may get different results with different reagents, times and concentrations hence the need for protocol optimization. The distortion of the cell morphology is something to bear in mind when interpreting the images.

### Fixation

**Formaldehyde/paraformaldehyde:**  
Aldehyde fixatives cross-link proteins and generally preserve well the cell morphology. They are somewhat slower acting than organic solvents, especially for thick specimens. 4% formaldehyde for 10 min is a good starting point for mammalian cells.

(**Glutaraldehyde** preserves the cellular structure very well but causes strong autofluorescence and so is used mainly for EM.)

**Methanol**   
Organic solvents like methanol precipitate proteins, which produces a similar outcome to crosslinking with aldehydes - the protein "shell" of the cell is maintained, but all the small molecules within will be lost during the rest of the protocol. Fixation with methanol denatures proteins, so never use if you have a fluorescent protein that you want to look at in your sample.
Some antigenic epitopes are in fact completely destroyed by methanol. However, it might also be advantageous for some other antibodies (especially some monoclonal antibodies which bind only one epitope) that the naturally buried antigens could be exposed after methanol fixation.
Methanol/Acetone Using a combination of methanol and acetone can improve immunolabelling lost in 100% methanol fixation (methanol is best for structure such as microtubules, acetone permeabilize well and is less damaging). Try few min in solvent at -20°C as a starting point.

### Permeabilization

Permeabilization helps get the antibodies into your now-fixed cells. A range of different detergents can be used, including NP-40, Triton X-100, Tween-20 and Saponin. Other solvents (eg ethanol or DMSO) can also be used to remove lipid. The fixation step actually permeabilizes the cells to some degree (ie they remove some of the membranes), so these steps aren't really completely distinct (eg Acetone permeabilizes as well as fixes).

The extent of permeabilization required depends on what you are trying to look at. For example, cell surface proteins don't require much/any permeabilization, indeed, if you remove all the membrane you will lose your protein. Labeling before permeabilization can also help distinguish extracellular subjects (eg cell surface-bound bacteria) and that within the cells (which only stains after permeabilization).

> Note: Your staining will be improved by blocking the non-specific binding of your antibody to your specimen. BSA, milk or serum can be used for this. Don't use serum from the same species as the one in which the primary antibody was raised! </br>
If you use a secondary antibody developed from goat, a typical blocking solution is 5% normal goat serum made in PBS (some people also add 0.05% Tween-20 to the solution). NaN3 can be added to 0.05% (w/v) to the solution. Blocking can last from 10 minutes to 30 minutes.

***

## 4. Mounting and Recording medium

### Mounting medium

Mounting medium helps preserve your sample and raises the refractive index to give good performance with oil objectives. Mountants often have scavengers which soak-up free radicals and reduce photobleaching (these sometimes reduce the initial brightness of your samples).

A glycerol-PBS mixture is suitable for most fixed immunofluorescence and GFP-labeled samples, using from 50-90% glycerol, 1x final PBS, and pH 8-9.
An antifading additive is highly recommended. Time and the act of observation both accelerate the loss of fluorescence from any sample. This inevitable process can be slowed by adding various reagents, chiefly antioxidants and radical scavengers, to the mounting medium.

Commercial products are available, such as (in no particular order):

- Fluoromount-G (Electron Microscopy Sciences): phosphate buffered glycerol + 10% polyvinyl alcohol + 0.1% sodium azide.
- Aqua/Poly-Mount (Polysciences)
- ProLong, SlowFade, SlowFade Light (Molecular Probes):
- Vectashield (Vector Laboratories)
- Immumount (Shandon)

### Recording medium

I will not go too much into details here as it really depend on your cells.
+ Avoid imaging with red-phenol as it will add a great amount of background.
+ If you are having trouble problems with cell death or damage during fluorescence imaging, several commercial products are available to minimize phototoxicity:  

- [Evrogen](http://evrogen.com/products/medium_DMEM_gfp/medium_DMEM_gfp.shtml)
-  [Thermofisher](http://www.thermofisher.com/us/en/home/life-science/cell-culture/mammalian-cell-culture/classical-media/fluorobrite-media.html)
- [Cell guidance systems](http://www.cellgs.com/Shop/Cell-Culture-Systems/LiveLight.html)

<FORM><INPUT Type="button" VALUE="Back" onClick="history.go(-1);return true;"></FORM>
