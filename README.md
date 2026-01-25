
<div align="center">
  <a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=KMGeon&utm_content=farm">
    <img src="https://render.gitanimals.org/farms/KMGeon" width="600" alt="Git Animals Farm"/>
  </a>
</div>

## Open Source Contribution

**spring-batch**
- [#5188](https://github.com/spring-projects/spring-batch/issues/5188) - 병렬 청크 처리 시 `StepContribution`의 `filterCount`, `processSkipCount`에서 발생하는 race condition 수정
- Regression Bug 수정
  - [#5220](https://github.com/spring-projects/spring-batch/issues/5220) - `MongoStepExecutionDao.countStepExecutions()`에서 `stepName` 파라미터가 무시되어 `startLimit` 기능이 동작하지 않는 버그 수정
  - [#5238](https://github.com/spring-projects/spring-batch/issues/5238) - `SimpleStepExecutionSplitter`에서 COMPLETED 파티션이 `allowStartIfComplete=true`여도 재시작되지 않는 버그 수정
- [#5217](https://github.com/spring-projects/spring-batch/issues/5217) - Graceful shutdown 시 race condition으로 인한 `OptimisticLockingFailureException` 발생 버그 수정
- [#5050](https://github.com/spring-projects/spring-batch/pull/5050), [#5052](https://github.com/spring-projects/spring-batch/pull/5052) - `JobParameter`, `JobOperatorTestUtils` 생성자의 null 체크 및 에러 메시지 오타 수정
