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
# Warmup Iteration   1: 1.559 ops/ms
Iteration   1: 6.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.948 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.851 ops/ms
Iteration   1: 11.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.781 ops/ms


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
# Warmup Iteration   1: 5.728 ops/ms
Iteration   1: 13.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.018 ops/ms


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
# Warmup Iteration   1: 5.356 ops/ms
Iteration   1: 8.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.610 ops/ms


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.069 ms/op
Iteration   1: 2.012 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.012 ms/op


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
# Warmup Iteration   1: 2.874 ±(99.9%) 0.041 ms/op
Iteration   1: 1.809 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.809 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.309 ±(99.9%) 0.055 ms/op
Iteration   1: 2.273 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.273 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.658 ±(99.9%) 0.096 ms/op
Iteration   1: 3.873 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.873 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.452 ±(99.9%) 0.085 ms/op
Iteration   1: 2.180 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.437 ms/op
                 createUser·p0.50:   2.046 ms/op
                 createUser·p0.90:   2.540 ms/op
                 createUser·p0.95:   2.752 ms/op
                 createUser·p0.99:   4.884 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 20.628 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14981
  mean =      2.180 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13303 
    [ 2.500,  5.000) = 1535 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.752 ms/op
     p(99.0000) =      4.884 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     20.628 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.105 ms/op
Iteration   1: 2.069 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   1.972 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   4.518 ms/op
                 existUser·p0.999:  17.385 ms/op
                 existUser·p0.9999: 17.742 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15443
  mean =      2.069 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 187 
    [ 1.250,  2.500) = 14069 
    [ 2.500,  3.750) = 984 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      4.518 ms/op
     p(99.9000) =     17.385 ms/op
     p(99.9900) =     17.742 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.188 ±(99.9%) 0.072 ms/op
Iteration   1: 2.151 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.484 ms/op
                 getUser·p0.50:   2.075 ms/op
                 getUser·p0.90:   2.691 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   3.486 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 13.477 ms/op
                 getUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14885
  mean =      2.151 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 164 
    [ 1.250,  2.500) = 11527 
    [ 2.500,  3.750) = 3069 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     13.477 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.125 ms/op
Iteration   1: 3.631 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  32.387 ms/op
                 listUser·p0.9999: 32.801 ms/op
                 listUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8806
  mean =      3.631 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1194 
    [ 2.500,  5.000) = 7416 
    [ 5.000,  7.500) = 164 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     32.387 ms/op
     p(99.9900) =     32.801 ms/op
     p(99.9990) =     32.801 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.948          ops/ms
ClientSimple.existUser                       thrpt         11.781          ops/ms
ClientSimple.getUser                         thrpt         13.018          ops/ms
ClientSimple.listUser                        thrpt          8.610          ops/ms
ClientSimple.createUser                       avgt          2.012           ms/op
ClientSimple.existUser                        avgt          1.809           ms/op
ClientSimple.getUser                          avgt          2.273           ms/op
ClientSimple.listUser                         avgt          3.873           ms/op
ClientSimple.createUser                     sample  14981   2.180 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.437           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.046           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.752           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.884           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.071           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.628           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.677           ms/op
ClientSimple.existUser                      sample  15443   2.069 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.763           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.972           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.518           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.385           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.742           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.760           ms/op
ClientSimple.getUser                        sample  14885   2.151 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.484           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.075           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.486           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.730           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.477           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.517           ms/op
ClientSimple.listUser                       sample   8806   3.631 ± 0.066   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.219           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.674           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.751           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.387           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.801           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.801           ms/op

Benchmark result is saved to 1713788165302.json
