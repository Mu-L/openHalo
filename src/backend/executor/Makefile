#-------------------------------------------------------------------------
#
# Makefile--
#    Makefile for executor
#
# IDENTIFICATION
#    src/backend/executor/Makefile
#
#-------------------------------------------------------------------------

subdir = src/backend/executor
top_builddir = ../../..
include $(top_builddir)/src/Makefile.global

OBJS = \
	execAmi.o \
	execAsync.o \
	execCurrent.o \
	execExpr.o \
	execExprInterp.o \
	execGrouping.o \
	execIndexing.o \
	execJunk.o \
	execMain.o \
	execParallel.o \
	execPartition.o \
	execProcnode.o \
	execReplication.o \
	execSRF.o \
	execScan.o \
	execTuples.o \
	execUtils.o \
	functions.o \
	instrument.o \
	nodeAgg.o \
	nodeAppend.o \
	nodeBitmapAnd.o \
	nodeBitmapHeapscan.o \
	nodeBitmapIndexscan.o \
	nodeBitmapOr.o \
	nodeCtescan.o \
	nodeCustom.o \
	nodeForeignscan.o \
	nodeFunctionscan.o \
	nodeGather.o \
	nodeGatherMerge.o \
	nodeGroup.o \
	nodeHash.o \
	nodeHashjoin.o \
	nodeIncrementalSort.o \
	nodeIndexonlyscan.o \
	nodeIndexscan.o \
	nodeLimit.o \
	nodeLockRows.o \
	nodeMaterial.o \
	nodeMemoize.o \
	nodeMergeAppend.o \
	nodeMergejoin.o \
	nodeModifyTable.o \
	nodeNamedtuplestorescan.o \
	nodeNestloop.o \
	nodeProjectSet.o \
	nodeRecursiveunion.o \
	nodeResult.o \
	nodeSamplescan.o \
	nodeSeqscan.o \
	nodeSetOp.o \
	nodeSort.o \
	nodeSubplan.o \
	nodeSubqueryscan.o \
	nodeTableFuncscan.o \
	nodeTidrangescan.o \
	nodeTidscan.o \
	nodeUnique.o \
	nodeValuesscan.o \
	nodeWindowAgg.o \
	nodeWorktablescan.o \
	spi.o \
	tqueue.o \
	tstoreReceiver.o \
	executor_engine.o \
	executor_ep.o \
	mys_executor.o \
	mys_execProcnode.o \
	mys_execMain.o \
	mys_execPartition.o \
	mys_nodeModifyTable.o 

include $(top_srcdir)/src/backend/common.mk
