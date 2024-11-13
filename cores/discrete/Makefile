discrete.v:
	ln -s ../../../../discrete.v
	ln -s ../../../discrete_rvfi_monitor.vh .

checks: discrete.v
	python3 ../../checks/genchecks.py
	$(MAKE) -C checks

check: checks

clean:
	rm -f discrete.v
	rm -f discrete_rvfi_monitor.vh
	rm -rf checks
