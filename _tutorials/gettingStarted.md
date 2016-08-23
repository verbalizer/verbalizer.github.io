---
layout : tutorial
title : Getting started with Verbalizer
---

This small tutorial will guide you through your first few steps with
the verbalizer plugin.
We will load an ontology and get an explanation for an inferred subsumption.

1.  Firstly, open Protege.

2.  Load an existing ontology or generate a new one. You can download a small
    ontology
    [here](/data/party.owl). If you want to build your own ontology, checkout
    this article about [how to engineer your ontology for the best experience](/index.html).
![alttext: open_ontology](/images/open_ontology.png "open ontology")

3.  Start a reasoner ([fact++](http://owl.man.ac.uk/factplusplus/)is recommended).
![alttext: start_reasoner](/images/start_reasoner.png "start reasoner")

4.  Switch to the entities tab. If the plugin was installed correct,
    you should see small question mark icons on the right site in the class description view.
    If you don't see this view, enable it via *Views > Class views > Description*
![alttext: click_qm](/images/click_qm.png "click question mark")

5.  Click the question mark icon of the inferred subsumption that
    you want to get the explanation from. You will notice, that some expressions
    are colored. If you hover over these, a tooltip text does pop up.  
![alttext: inference_explained](/images/inference_explained.png "inference explained")
