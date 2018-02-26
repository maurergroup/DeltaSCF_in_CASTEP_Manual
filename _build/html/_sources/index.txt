.. DeltaSCF-CASTEP-Module documentation master file, created by
   sphinx-quickstart on Tue Sep 11 10:27:22 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

DeltaSCF-CASTEP-Module
==================================================

This document explains the use of the deltascf.f90 module in 
CASTEP version 17.1. This module has been developed at the Technische Universität München. 
This module allows to calculate excited states via :math:`\Delta`\SCF calculations of different 
kinds as well as to apply penalty potentials to reference 
orbitals. It also allows to calculate the projected DOS onto these 
reference orbitals with the post-processor MolPDOS.

The corresponding references are:

* for le :math:`\Delta`\SCF and MolPDOS: R. J. Maurer and K. Reuter, `J. Chem. Phys. 139, 014708 (2013)`_

* for DFT+U(MO): M. Müller, K. Diller, R. J. Maurer, and K. Reuter, `J. Chem. Phys. 144, 024701 (2016)`_

* for :math:`\Delta`\SCF-DFT see also: R. J. Maurer, and K. Reuter, `J. Chem. Phys. 135, 224303 (2011)`_

.. _J. Chem. Phys. 139, 014708 (2013): http://scitation.aip.org/content/aip/journal/jcp/139/1/10.1063/1.4812398

.. _J. Chem. Phys. 144, 024701 (2016): http://scitation.aip.org/content/aip/journal/jcp/144/2/10.1063/1.4938259

.. _J. Chem. Phys. 135, 224303 (2011): http://scitation.aip.org/content/aip/journal/jcp/135/22/10.1063/1.3664305

or

First-Principles Description of the Isomerization Dynamics of Surface-Adsorbed Molecular Switches, `Doctoral Thesis`_, Technische Universität München, 2014

.. _Doctoral Thesis: http://mediatum.ub.tum.de/?id=1190934

Here is a list of publications, which have employed functionality from this module:

* R. J. Maurer, K. Reuter, "Bistability Loss as a Key Feature in Azobenzene (Non-) Switching on Metal Surfaces", Angew. Chem. Int. Ed. **51**, 12009-12011 (2012)

* T. G. Gopakumar, T. Davran-Candan *et al.*, "Broken Symmetry of an Adsorbed Molecular Switch Determined by Scanning Tunneling Spectroscopy", Angew. Chem. Int. Ed. **52**, 11007-11010, (2013)

* K. Scheil, T. G. Gopakumar, *et al.*, "Switching of an Azobenzene-Tripod Molecule on Ag(111)", J. Phys. Chem. Lett. **7**, 2080-2084 (2016)

* S. Karan, N. Li, *et al.*, "Spin Manipulation by Creation of Single-Molecule Radical Cations", Phys. Rev. Lett. **116**, 027201 (2016)

* M. Müller, K. Diller, R. J. Maurer, K. Reuter, "Interfacial charge rearrangement and intermolecular interactions: Density-functional theory study of free-base porphine adsorbed on Ag(111) and Cu(111)", J. Chem. Phys. **144**, 024701, (2016)

For more information, please contact reinhard.maurer@yale.edu

========
Contents
========

.. toctree:: 
   :maxdepth: 2

   Overview<overview>
   Conventional DeltaSCF<classic>
   Linear expansion DeltaSCF<ledscf>
   DFT+U(MO)<dft_u>
   Molecular Orbital projected DOS - MolPDOS<molpdos>

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

