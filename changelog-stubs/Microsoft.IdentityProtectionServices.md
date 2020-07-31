### Identity and access (Azure AD)

| **Change type** | **Version** | **Description** |
|:---|:---|:---|
|Addition|beta|Added the **includeProtectionLevels** property to [conditionalAccessApplications](/graph/api/resources/conditionalAccessApplications?view=graph-rest-beta) resource|
|Addition|beta|Added the **includeDeviceRule** property to [conditionalAccessDevices](/graph/api/resources/conditionalAccessDevices?view=graph-rest-beta) resource|
|Addition|beta|Added the **excludeDeviceRule** property to [conditionalAccessDevices](/graph/api/resources/conditionalAccessDevices?view=graph-rest-beta) resource|
|Addition|beta|Added the **times** property to [conditionalAccessConditionSet](/graph/api/resources/conditionalAccessConditionSet?view=graph-rest-beta) resource|
|Addition|beta|Added the **protectionLevels** relationship to [conditionalAccessRoot](/graph/api/resources/conditionalAccessRoot?view=graph-rest-beta) resource|
|Addition|beta|Added the **continuousAccessEvaluationPolicy** relationship to [identityContainer](/graph/api/resources/identityContainer?view=graph-rest-beta) resource|
|Addition|beta|Added the **identityProtectionNotificationPolicy** relationship to [policyRoot](/graph/api/resources/policyRoot?view=graph-rest-beta) resource|
|Addition|beta|Added the [identityUserRisk](/graph/api/resources/identityUserRisk?view=graph-rest-beta) resource type|
|Addition|beta|Added the [conditionalAccessDays](/graph/api/resources/conditionalAccessDays?view=graph-rest-beta) resource type|
|Addition|beta|Added the [conditionalAccessTimeRange](/graph/api/resources/conditionalAccessTimeRange?view=graph-rest-beta) resource type|
|Addition|beta|Added the [conditionalAccessTimes](/graph/api/resources/conditionalAccessTimes?view=graph-rest-beta) resource type|
|Addition|beta|Added the [identityRiskEvent](/graph/api/resources/identityRiskEvent?view=graph-rest-beta) resource type|
|Addition|beta|Added the [locatedRiskEvent](/graph/api/resources/locatedRiskEvent?view=graph-rest-beta) resource type|
|Addition|beta|Added the [impossibleTravelRiskEvent](/graph/api/resources/impossibleTravelRiskEvent?view=graph-rest-beta) resource type|
|Addition|beta|Added the [leakedCredentialsRiskEvent](/graph/api/resources/leakedCredentialsRiskEvent?view=graph-rest-beta) resource type|
|Addition|beta|Added the [anonymousIpRiskEvent](/graph/api/resources/anonymousIpRiskEvent?view=graph-rest-beta) resource type|
|Addition|beta|Added the [suspiciousIpRiskEvent](/graph/api/resources/suspiciousIpRiskEvent?view=graph-rest-beta) resource type|
|Addition|beta|Added the [unfamiliarLocationRiskEvent](/graph/api/resources/unfamiliarLocationRiskEvent?view=graph-rest-beta) resource type|
|Addition|beta|Added the [malwareRiskEvent](/graph/api/resources/malwareRiskEvent?view=graph-rest-beta) resource type|
|Addition|beta|Added the [weeklyDigestSettings](/graph/api/resources/weeklyDigestSettings?view=graph-rest-beta) resource type|
|Addition|beta|Added the [userAlertsSettings](/graph/api/resources/userAlertsSettings?view=graph-rest-beta) resource type|
|Addition|beta|Added the [identityProtectionNotificationPolicy](/graph/api/resources/identityProtectionNotificationPolicy?view=graph-rest-beta) resource type|
|Addition|beta|Added the [baselineProtectionPolicy](/graph/api/resources/baselineProtectionPolicy?view=graph-rest-beta) resource type|
|Addition|beta|Added the [continuousAccessEvaluationPolicy](/graph/api/resources/continuousAccessEvaluationPolicy?view=graph-rest-beta) resource type|
|Addition|beta|Added the [protectionLevel](/graph/api/resources/protectionLevel?view=graph-rest-beta) resource type|
|Addition|beta|Added the `federatedMfa` member to the **conditionalAccessGrantControl** enumeration|
|Addition|beta|Added the `federatedCertAuth` member to the **conditionalAccessGrantControl** enumeration|
|Addition|beta|Added the **riskEventStatus** enumeration type|
|Addition|beta|Added the **userRiskLevel** enumeration type|
|Addition|beta|Added the **continuousAccessEvaluationMode** enumeration type|
|Addition|beta|Added the **conditionalAccessDayOfWeek** enumeration type|
|Addition|beta|Added the **baselineProtectionPolicyState** enumeration type|
|Deletion|beta|Removed the `passwordChange` member from the **conditionalAccessGrantControl** enumeration|
|Deletion|beta|Removed the `unknownFutureValue` member from the **conditionalAccessGrantControl** enumeration|
