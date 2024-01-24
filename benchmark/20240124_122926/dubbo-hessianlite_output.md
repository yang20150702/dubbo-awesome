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
# Warmup Iteration   1: 2.388 ops/ms
Iteration   1: 6.619 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.619 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.206 ops/ms
Iteration   1: 12.983 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.983 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.723 ops/ms
Iteration   1: 8.535 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.535 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.238 ops/ms
Iteration   1: 3.563 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.563 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.102 ±(99.9%) 0.081 ms/op
Iteration   1: 3.050 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.050 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ±(99.9%) 0.031 ms/op
Iteration   1: 2.024 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.024 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.327 ±(99.9%) 0.040 ms/op
Iteration   1: 3.169 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.169 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.031 ±(99.9%) 0.409 ms/op
Iteration   1: 9.271 ±(99.9%) 0.128 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.271 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.885 ±(99.9%) 0.098 ms/op
Iteration   1: 2.941 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.785 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  12.749 ms/op
                 createUser·p0.9999: 13.471 ms/op
                 createUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10881
  mean =      2.941 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 3887 
    [ 2.500,  3.750) = 5895 
    [ 3.750,  5.000) = 810 
    [ 5.000,  6.250) = 146 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     12.749 ms/op
     p(99.9900) =     13.471 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ±(99.9%) 0.099 ms/op
Iteration   1: 1.952 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.479 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.305 ms/op
                 existUser·p0.999:  4.948 ms/op
                 existUser·p0.9999: 5.110 ms/op
                 existUser·p1.00:   5.136 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16421
  mean =      1.952 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 77 
    [1.000, 1.500) = 1817 
    [1.500, 2.000) = 7737 
    [2.000, 2.500) = 5528 
    [2.500, 3.000) = 1013 
    [3.000, 3.500) = 110 
    [3.500, 4.000) = 41 
    [4.000, 4.500) = 34 
    [4.500, 5.000) = 58 
    [5.000, 5.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.305 ms/op
     p(99.9000) =      4.948 ms/op
     p(99.9900) =      5.110 ms/op
     p(99.9990) =      5.136 ms/op
     p(99.9999) =      5.136 ms/op
    p(100.0000) =      5.136 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.499 ±(99.9%) 0.105 ms/op
Iteration   1: 3.222 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.794 ms/op
                 getUser·p0.999:  17.123 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9929
  mean =      3.222 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1741 
    [ 2.500,  3.750) = 6579 
    [ 3.750,  5.000) = 1282 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.794 ms/op
     p(99.9000) =     17.123 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.921 ±(99.9%) 0.594 ms/op
Iteration   1: 8.431 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   8.217 ms/op
                 listUser·p0.90:   11.076 ms/op
                 listUser·p0.95:   12.206 ms/op
                 listUser·p0.99:   14.440 ms/op
                 listUser·p0.999:  19.602 ms/op
                 listUser·p0.9999: 25.428 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3793
  mean =      8.431 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 128 
    [ 5.000,  7.500) = 1129 
    [ 7.500, 10.000) = 1821 
    [10.000, 12.500) = 546 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      8.217 ms/op
     p(90.0000) =     11.076 ms/op
     p(95.0000) =     12.206 ms/op
     p(99.0000) =     14.440 ms/op
     p(99.9000) =     19.602 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.619          ops/ms
Client.existUser                       thrpt         12.983          ops/ms
Client.getUser                         thrpt          8.535          ops/ms
Client.listUser                        thrpt          3.563          ops/ms
Client.createUser                       avgt          3.050           ms/op
Client.existUser                        avgt          2.024           ms/op
Client.getUser                          avgt          3.169           ms/op
Client.listUser                         avgt          9.271           ms/op
Client.createUser                     sample  10881   2.941 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.071           ms/op
Client.createUser:createUser·p0.50    sample          2.785           ms/op
Client.createUser:createUser·p0.90    sample          3.752           ms/op
Client.createUser:createUser·p0.95    sample          4.190           ms/op
Client.createUser:createUser·p0.99    sample          6.537           ms/op
Client.createUser:createUser·p0.999   sample         12.749           ms/op
Client.createUser:createUser·p0.9999  sample         13.471           ms/op
Client.createUser:createUser·p1.00    sample         13.484           ms/op
Client.existUser                      sample  16421   1.952 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.479           ms/op
Client.existUser:existUser·p0.50      sample          1.923           ms/op
Client.existUser:existUser·p0.90      sample          2.417           ms/op
Client.existUser:existUser·p0.95      sample          2.642           ms/op
Client.existUser:existUser·p0.99      sample          3.305           ms/op
Client.existUser:existUser·p0.999     sample          4.948           ms/op
Client.existUser:existUser·p0.9999    sample          5.110           ms/op
Client.existUser:existUser·p1.00      sample          5.136           ms/op
Client.getUser                        sample   9929   3.222 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample          0.905           ms/op
Client.getUser:getUser·p0.50          sample          3.146           ms/op
Client.getUser:getUser·p0.90          sample          3.990           ms/op
Client.getUser:getUser·p0.95          sample          4.440           ms/op
Client.getUser:getUser·p0.99          sample          6.794           ms/op
Client.getUser:getUser·p0.999         sample         17.123           ms/op
Client.getUser:getUser·p0.9999        sample         19.137           ms/op
Client.getUser:getUser·p1.00          sample         19.137           ms/op
Client.listUser                       sample   3793   8.431 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          1.747           ms/op
Client.listUser:listUser·p0.50        sample          8.217           ms/op
Client.listUser:listUser·p0.90        sample         11.076           ms/op
Client.listUser:listUser·p0.95        sample         12.206           ms/op
Client.listUser:listUser·p0.99        sample         14.440           ms/op
Client.listUser:listUser·p0.999       sample         19.602           ms/op
Client.listUser:listUser·p0.9999      sample         25.428           ms/op
Client.listUser:listUser·p1.00        sample         25.428           ms/op
