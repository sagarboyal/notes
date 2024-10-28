failed test for getSynchronousSfSyncResponseReturnsSuccessForValidApplicationIdAndStageUW_APPROVAL():Cannot invoke "com.mahindrafinance.fos.commons.api.response.MfResponse.getData()" because "loanDetailsResponse" is null
java.lang.NullPointerException: Cannot invoke "com.mahindrafinance.fos.commons.api.response.MfResponse.getData()" because "loanDetailsResponse" is null
	at com.mahindrafinance.fos.service.sfsync.SfService.getSynchronousSfSyncResponse(SfService.java:404)



Failed test for:getSynchronousSfSyncResponseReturnsSuccessForValidApplicationIdAndUW_APPROVAL()
 Applicant id not found for the given application id
com.mahindrafinance.fos.commons.exceptions.InvalidRequestException: Applicant id not found for the given application id
	at com.mahindrafinance.fos.service.sfsync.SfService.lambda$getApplicantMappingByApplicationId$51(SfService.java:2813)
	at java.base/java.util.Optional.orElseThrow(Optional.java:403)
	at com.mahindrafinance.fos.service.sfsync.SfService.getApplicantMappingByApplicationId(SfService.java:2813)
	at com.mahindrafinance.fos.service.sfsync.SfService.syncAddOnProducts(SfService.java:488)
	at com.mahindrafinance.fos.service.sfsync.SfService.getSynchronousSfSyncResponse(SfService.java:353)
