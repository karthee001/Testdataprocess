
generate-undertow-bin:
	protoc \
	--plugin=${PWD}/protoc-gen-dump \
	--dump_out=target=server,type=undertow:../java  \
	./status.proto
