coleman_jacob_patra_sayan_neal_2011_an_exploration_of_hmc.pdf:coleman_jacob_patra_sayan_neal_2011_an_exploration_of_hmc.tex HMC_eg.png HMC_critical_stepsize.png MH_HMC_double_position.png MH_HMC_single_position.png 100d_iterations.png 100d_means.png 100d_sds.png window_iter_2d.png window_iter_10d.png WHMC_parallel.png
	pdflatex coleman_jacob_patra_sayan_neal_2011_an_exploration_of_hmc.tex
	pdflatex coleman_jacob_patra_sayan_neal_2011_an_exploration_of_hmc.tex

663_project_code.py: 663_project_code.ipynb
	jupyter nbconvert --to python 663_project_code.ipynb

HMC_eg.png: pics

HMC_critical_stepsize.png: pics

MH_HMC_double_position.png: pics

MH_HMC_single_position.png: pics

100d_iterations.png: pics

100d_means.png: pics

100d_sds.png: pics

.PHONY: all, clean, pics

pics: 663_project_code.py
	python 663_project_code.py

all: coleman_jacob_patra_sayan_neal_2011_an_exploration_of_hmc.pdf

clean:
	rm -f *.o *.aux *.log *.py *.pytxcode *.out  *.png *.brf *.gz
