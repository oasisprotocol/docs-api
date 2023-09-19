PACKAGES: \
	packages/client \
	packages/client-ext-utils \
	packages/client-rt \
	packages/client-signer-ledger \
	packages/sapphire-paratime

docs:
	npm run docs

packages: $(PACKAGES)

packages/client:
	cp -r ../modules/oasis-sdk/client-sdk/ts-web/core $@

packages/client-ext-utils:
	cp -r ../modules/oasis-sdk/client-sdk/ts-web/ext-utils $@

packages/client-rt:
	cp -r ../modules/oasis-sdk/client-sdk/ts-web/rt $@

packages/client-signer-ledger:
	cp -r ../modules/oasis-sdk/client-sdk/ts-web/signer-ledger $@

packages/sapphire-paratime:
	cp -r ../modules/sapphire-paratime/clients/js $@

.PHONY: packages
