# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.042 ops/ms
Iteration   1: 6.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.824 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.849 ops/ms
Iteration   1: 15.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.103 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.308 ops/ms
Iteration   1: 14.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.276 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.348 ops/ms
Iteration   1: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.313 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ±(99.9%) 0.076 ms/op
Iteration   1: 2.242 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.242 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.479 ±(99.9%) 0.054 ms/op
Iteration   1: 1.931 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.203 ±(99.9%) 0.046 ms/op
Iteration   1: 2.090 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.090 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.070 ±(99.9%) 0.106 ms/op
Iteration   1: 3.755 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.755 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.393 ±(99.9%) 0.078 ms/op
Iteration   1: 1.953 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.501 ms/op
                 createUser·p0.50:   1.745 ms/op
                 createUser·p0.90:   2.699 ms/op
                 createUser·p0.95:   2.998 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  12.800 ms/op
                 createUser·p0.9999: 13.500 ms/op
                 createUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16368
  mean =      1.953 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 698 
    [ 1.250,  2.500) = 13229 
    [ 2.500,  3.750) = 2214 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =     12.800 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.235 ±(99.9%) 0.098 ms/op
Iteration   1: 1.720 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   1.657 ms/op
                 existUser·p0.90:   1.952 ms/op
                 existUser·p0.95:   2.167 ms/op
                 existUser·p0.99:   2.892 ms/op
                 existUser·p0.999:  13.079 ms/op
                 existUser·p0.9999: 13.249 ms/op
                 existUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18723
  mean =      1.720 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 18182 
    [ 2.500,  3.750) = 308 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.657 ms/op
     p(90.0000) =      1.952 ms/op
     p(95.0000) =      2.167 ms/op
     p(99.0000) =      2.892 ms/op
     p(99.9000) =     13.079 ms/op
     p(99.9900) =     13.249 ms/op
     p(99.9990) =     13.320 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.122 ±(99.9%) 0.071 ms/op
Iteration   1: 2.192 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.159 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.892 ms/op
                 getUser·p0.99:   3.720 ms/op
                 getUser·p0.999:  11.502 ms/op
                 getUser·p0.9999: 11.710 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14587
  mean =      2.192 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 279 
    [ 1.250,  2.500) = 10872 
    [ 2.500,  3.750) = 3295 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      3.720 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     11.710 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.842 ±(99.9%) 0.148 ms/op
Iteration   1: 3.873 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.019 ms/op
                 listUser·p0.999:  64.160 ms/op
                 listUser·p0.9999: 67.240 ms/op
                 listUser·p1.00:   67.240 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8318
  mean =      3.873 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7993 
    [ 5.000, 10.000) = 272 
    [10.000, 15.000) = 7 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 5 
    [60.000, 65.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.019 ms/op
     p(99.9000) =     64.160 ms/op
     p(99.9900) =     67.240 ms/op
     p(99.9990) =     67.240 ms/op
     p(99.9999) =     67.240 ms/op
    p(100.0000) =     67.240 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.824          ops/ms
ClientSimple.existUser                       thrpt         15.103          ops/ms
ClientSimple.getUser                         thrpt         14.276          ops/ms
ClientSimple.listUser                        thrpt          8.313          ops/ms
ClientSimple.createUser                       avgt          2.242           ms/op
ClientSimple.existUser                        avgt          1.931           ms/op
ClientSimple.getUser                          avgt          2.090           ms/op
ClientSimple.listUser                         avgt          3.755           ms/op
ClientSimple.createUser                     sample  16368   1.953 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.501           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.745           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.964           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.800           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.500           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.500           ms/op
ClientSimple.existUser                      sample  18723   1.720 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.624           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.657           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.892           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.079           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.249           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.320           ms/op
ClientSimple.getUser                        sample  14587   2.192 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.616           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.720           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.502           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.710           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.747           ms/op
ClientSimple.listUser                       sample   8318   3.873 ± 0.123   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.143           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.658           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.019           ms/op
ClientSimple.listUser:listUser·p0.999       sample         64.160           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         67.240           ms/op
ClientSimple.listUser:listUser·p1.00        sample         67.240           ms/op

Benchmark result is saved to 1710915072674.json
