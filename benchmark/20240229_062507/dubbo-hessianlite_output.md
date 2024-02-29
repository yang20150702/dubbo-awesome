# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.272 ops/ms
Iteration   1: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.907 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.306 ops/ms
Iteration   1: 13.446 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.446 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.288 ops/ms
Iteration   1: 8.172 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.172 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.770 ops/ms
Iteration   1: 3.337 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.337 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.076 ±(99.9%) 0.100 ms/op
Iteration   1: 3.240 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.240 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ±(99.9%) 0.038 ms/op
Iteration   1: 1.873 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.873 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.965 ±(99.9%) 0.065 ms/op
Iteration   1: 3.005 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.005 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.514 ±(99.9%) 0.167 ms/op
Iteration   1: 8.449 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.449 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.409 ±(99.9%) 0.130 ms/op
Iteration   1: 3.352 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   15.444 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 35.914 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9539
  mean =      3.352 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1513 
    [ 2.500,  5.000) = 7596 
    [ 5.000,  7.500) = 223 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =     15.444 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.817 ±(99.9%) 0.064 ms/op
Iteration   1: 1.657 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.393 ms/op
                 existUser·p0.50:   1.585 ms/op
                 existUser·p0.90:   1.923 ms/op
                 existUser·p0.95:   2.061 ms/op
                 existUser·p0.99:   3.236 ms/op
                 existUser·p0.999:  17.662 ms/op
                 existUser·p0.9999: 18.320 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19296
  mean =      1.657 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 824 
    [ 1.250,  2.500) = 18143 
    [ 2.500,  3.750) = 216 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      1.585 ms/op
     p(90.0000) =      1.923 ms/op
     p(95.0000) =      2.061 ms/op
     p(99.0000) =      3.236 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     18.320 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.811 ±(99.9%) 0.133 ms/op
Iteration   1: 3.398 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   8.002 ms/op
                 getUser·p0.999:  14.919 ms/op
                 getUser·p0.9999: 16.056 ms/op
                 getUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9417
  mean =      3.398 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1390 
    [ 2.500,  3.750) = 5903 
    [ 3.750,  5.000) = 1823 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      8.002 ms/op
     p(99.9000) =     14.919 ms/op
     p(99.9900) =     16.056 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.932 ±(99.9%) 0.448 ms/op
Iteration   1: 9.205 ±(99.9%) 0.236 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   8.479 ms/op
                 listUser·p0.90:   12.108 ms/op
                 listUser·p0.95:   13.951 ms/op
                 listUser·p0.99:   29.999 ms/op
                 listUser·p0.999:  42.986 ms/op
                 listUser·p0.9999: 47.710 ms/op
                 listUser·p1.00:   47.710 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3464
  mean =      9.205 ±(99.9%) 0.236 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 93 
    [ 5.000, 10.000) = 2419 
    [10.000, 15.000) = 813 
    [15.000, 20.000) = 73 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 25 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      8.479 ms/op
     p(90.0000) =     12.108 ms/op
     p(95.0000) =     13.951 ms/op
     p(99.0000) =     29.999 ms/op
     p(99.9000) =     42.986 ms/op
     p(99.9900) =     47.710 ms/op
     p(99.9990) =     47.710 ms/op
     p(99.9999) =     47.710 ms/op
    p(100.0000) =     47.710 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.907          ops/ms
Client.existUser                       thrpt         13.446          ops/ms
Client.getUser                         thrpt          8.172          ops/ms
Client.listUser                        thrpt          3.337          ops/ms
Client.createUser                       avgt          3.240           ms/op
Client.existUser                        avgt          1.873           ms/op
Client.getUser                          avgt          3.005           ms/op
Client.listUser                         avgt          8.449           ms/op
Client.createUser                     sample   9539   3.352 ± 0.069   ms/op
Client.createUser:createUser·p0.00    sample          1.114           ms/op
Client.createUser:createUser·p0.50    sample          2.961           ms/op
Client.createUser:createUser·p0.90    sample          4.145           ms/op
Client.createUser:createUser·p0.95    sample          4.776           ms/op
Client.createUser:createUser·p0.99    sample         15.444           ms/op
Client.createUser:createUser·p0.999   sample         25.100           ms/op
Client.createUser:createUser·p0.9999  sample         35.914           ms/op
Client.createUser:createUser·p1.00    sample         35.914           ms/op
Client.existUser                      sample  19296   1.657 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.393           ms/op
Client.existUser:existUser·p0.50      sample          1.585           ms/op
Client.existUser:existUser·p0.90      sample          1.923           ms/op
Client.existUser:existUser·p0.95      sample          2.061           ms/op
Client.existUser:existUser·p0.99      sample          3.236           ms/op
Client.existUser:existUser·p0.999     sample         17.662           ms/op
Client.existUser:existUser·p0.9999    sample         18.320           ms/op
Client.existUser:existUser·p1.00      sample         18.350           ms/op
Client.getUser                        sample   9417   3.398 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          0.798           ms/op
Client.getUser:getUser·p0.50          sample          3.338           ms/op
Client.getUser:getUser·p0.90          sample          4.162           ms/op
Client.getUser:getUser·p0.95          sample          4.571           ms/op
Client.getUser:getUser·p0.99          sample          8.002           ms/op
Client.getUser:getUser·p0.999         sample         14.919           ms/op
Client.getUser:getUser·p0.9999        sample         16.056           ms/op
Client.getUser:getUser·p1.00          sample         16.056           ms/op
Client.listUser                       sample   3464   9.205 ± 0.236   ms/op
Client.listUser:listUser·p0.00        sample          1.456           ms/op
Client.listUser:listUser·p0.50        sample          8.479           ms/op
Client.listUser:listUser·p0.90        sample         12.108           ms/op
Client.listUser:listUser·p0.95        sample         13.951           ms/op
Client.listUser:listUser·p0.99        sample         29.999           ms/op
Client.listUser:listUser·p0.999       sample         42.986           ms/op
Client.listUser:listUser·p0.9999      sample         47.710           ms/op
Client.listUser:listUser·p1.00        sample         47.710           ms/op
