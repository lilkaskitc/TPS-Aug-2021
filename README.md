# TPS-Aug-2021

Level 1: Base tree models of LGB, XGB, CatB. Tried versions with and without pseudo labels, where several different predictions from other Kagglers are used as the pseudo labels.

Level 2: Stacking on level 1 with metamodels of LGB, RF, MLP, input including both source data and base models results. Also built standalone strong XGB models. Only LGB no pseudo models stacking is tried, since no pseudo performance is less desirable and cannot share the Kfold with models utilising pseudo labels.

Level 3:
