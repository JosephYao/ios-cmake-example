set(Test_SRCS AuthenticationServiceTest.cc StubProfileDao.h StubRsaTokenDao.h MockLogger.h SimpleServiceTest.cc)

add_executable(cpp_otp_test ${Test_SRCS})
target_link_libraries(cpp_otp_test gtest gmock gtest_main fruit core)
