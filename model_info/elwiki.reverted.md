Model Information:
	 - type: GradientBoosting
	 - version: 0.4.0
	 - params: {'n_estimators': 500, 'init': None, 'multilabel': False, 'label_weights': OrderedDict([(True, 10)]), 'random_state': None, 'min_impurity_split': None, 'min_samples_split': 2, 'min_weight_fraction_leaf': 0.0, 'min_impurity_decrease': 0.0, 'presort': 'auto', 'center': True, 'criterion': 'friedman_mse', 'max_features': 'log2', 'population_rates': None, 'max_leaf_nodes': None, 'min_samples_leaf': 1, 'subsample': 1.0, 'max_depth': 7, 'warm_start': False, 'labels': [True, False], 'scale': True, 'verbose': 0, 'loss': 'deviance', 'learning_rate': 0.01}
	Environment:
	 - revscoring_version: '2.2.5'
	 - platform: 'Linux-4.9.0-6-amd64-x86_64-with-debian-9.4'
	 - machine: 'x86_64'
	 - version: '#1 SMP Debian 4.9.82-1+deb9u3 (2018-03-02)'
	 - system: 'Linux'
	 - processor: ''
	 - python_build: ('default', 'Jan 19 2017 14:11:04')
	 - python_compiler: 'GCC 6.3.0 20170118'
	 - python_branch: ''
	 - python_implementation: 'CPython'
	 - python_revision: ''
	 - python_version: '3.5.3'
	 - release: '4.9.0-6-amd64'
	
	Statistics:
	counts (n=19865):
		label        n         ~True    ~False
		-------  -----  ---  -------  --------
		True       845  -->      517       328
		False    19020  -->     1201     17819
	rates:
		              True    False
		----------  ------  -------
		sample       0.043    0.957
		population   0.052    0.948
	match_rate (micro=0.866, macro=0.5):
		  False    True
		-------  ------
		  0.908   0.092
	filter_rate (micro=0.134, macro=0.5):
		  False    True
		-------  ------
		  0.092   0.908
	recall (micro=0.92, macro=0.774):
		  False    True
		-------  ------
		  0.937   0.612
	!recall (micro=0.629, macro=0.774):
		  False    True
		-------  ------
		  0.612   0.937
	precision (micro=0.945, macro=0.662):
		  False    True
		-------  ------
		  0.978   0.346
	!precision (micro=0.378, macro=0.662):
		  False    True
		-------  ------
		  0.346   0.978
	f1 (micro=0.93, macro=0.699):
		  False    True
		-------  ------
		  0.957   0.442
	!f1 (micro=0.468, macro=0.699):
		  False    True
		-------  ------
		  0.442   0.957
	accuracy (micro=0.92, macro=0.92):
		  False    True
		-------  ------
		   0.92    0.92
	fpr (micro=0.371, macro=0.226):
		  False    True
		-------  ------
		  0.388   0.063
	roc_auc (micro=0.915, macro=0.915):
		  False    True
		-------  ------
		  0.915   0.915
	pr_auc (micro=0.966, macro=0.718):
		  False    True
		-------  ------
		  0.994   0.443
	
	 - score_schema: {'properties': {'prediction': {'description': 'The most likely label predicted by the estimator', 'type': 'bool'}, 'probability': {'description': 'A mapping of probabilities onto each of the potential output labels', 'properties': {'true': 'number', 'false': 'number'}, 'type': 'object'}}, 'title': 'Scikit learn-based classifier score with probability', 'type': 'object'}

