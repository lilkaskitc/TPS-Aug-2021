# TPS-Aug-2021

Level 1: Base tree models of LGB, XGB, CatB. Tried versions with and without pseudo labels, where several different predictions from other Kagglers are used as the pseudo labels.

Level 2: Stacking on level 1 with metamodels of LGB, RF, MLP. Also built standalone strong XGB models. No pseudo models stacking is tried and abandoned, since no pseudo performance is not desirable and cannot share the Kfold with models utilising pseudo labels.

Level 3:
