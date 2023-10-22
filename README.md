# RioPlatenseSpanish_Neurosurgery_Dataset

This Dataset of Rioplatense Spanish for medical triage tasks contains 123 phrases of patients that state or deny that they underwent a neurosurgery procedure.

The dataset comprises variations in: 
(1) lexemes; 
(2) verb tenses; 
(3) syntax; 
(4) negation modals; 
(5) Rioplatense discursive markers; 
(6) formal and informal registers. 


| TAG                                   | TRANSLATION                   |
|---------------------------------------|------------------------------ |
| ground_truth                          | ground_truth                  |
| presente                              | present                       |
| formal                                | formal                        |
| informal                              | informal                      |
| marcas_discursivas_rioplatenses       | Rioplatense discursive markers|
| negación                              | negation                      |
| voz_pasiva                            | passive voice                 |

'ground_truth' has two possible values: 
"4" means that they underwent a neurosurgery procedure.
"-1" means that they did NOT underwent a neurosurgery procedure.

For every other tag, "1" means that the phrase has the linguistic structure named in the tag, "0" means it doesn't. 
