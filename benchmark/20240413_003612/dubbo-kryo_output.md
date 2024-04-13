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
# Warmup Iteration   1: 1.884 ops/ms
Iteration   1: 7.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.325 ops/ms


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
# Warmup Iteration   1: 6.983 ops/ms
Iteration   1: 15.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.012 ops/ms


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
# Warmup Iteration   1: 5.753 ops/ms
Iteration   1: 12.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.624 ops/ms


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
# Warmup Iteration   1: 4.512 ops/ms
Iteration   1: 8.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.224 ops/ms


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.078 ms/op
Iteration   1: 2.200 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.200 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.049 ms/op
Iteration   1: 1.876 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.876 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.060 ms/op
Iteration   1: 2.076 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.076 ms/op


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
# Warmup Iteration   1: 5.085 ±(99.9%) 0.107 ms/op
Iteration   1: 3.632 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.632 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.092 ms/op
Iteration   1: 2.246 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.720 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   8.125 ms/op
                 createUser·p0.999:  17.074 ms/op
                 createUser·p0.9999: 18.804 ms/op
                 createUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14318
  mean =      2.246 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 233 
    [ 1.250,  2.500) = 11269 
    [ 2.500,  3.750) = 2518 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      8.125 ms/op
     p(99.9000) =     17.074 ms/op
     p(99.9900) =     18.804 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 3.120 ±(99.9%) 0.081 ms/op
Iteration   1: 1.987 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  13.876 ms/op
                 existUser·p0.9999: 13.949 ms/op
                 existUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16104
  mean =      1.987 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 14499 
    [ 2.500,  3.750) = 1185 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     13.876 ms/op
     p(99.9900) =     13.949 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.096 ms/op
Iteration   1: 2.020 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   5.057 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 12.758 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15824
  mean =      2.020 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 14645 
    [ 2.500,  3.750) = 891 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      5.057 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.758 ms/op
     p(99.9990) =     12.796 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


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
# Warmup Iteration   1: 5.473 ±(99.9%) 0.218 ms/op
Iteration   1: 3.680 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8735
  mean =      3.680 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 276 
    [ 2.500,  3.750) = 4869 
    [ 3.750,  5.000) = 3247 
    [ 5.000,  6.250) = 199 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.325          ops/ms
ClientSimple.existUser                       thrpt         15.012          ops/ms
ClientSimple.getUser                         thrpt         12.624          ops/ms
ClientSimple.listUser                        thrpt          8.224          ops/ms
ClientSimple.createUser                       avgt          2.200           ms/op
ClientSimple.existUser                        avgt          1.876           ms/op
ClientSimple.getUser                          avgt          2.076           ms/op
ClientSimple.listUser                         avgt          3.632           ms/op
ClientSimple.createUser                     sample  14318   2.246 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.591           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.101           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.125           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.074           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.804           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.874           ms/op
ClientSimple.existUser                      sample  16104   1.987 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.662           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.880           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.628           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.876           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.949           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.959           ms/op
ClientSimple.getUser                        sample  15824   2.020 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.610           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.057           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.042           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.758           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.796           ms/op
ClientSimple.listUser                       sample   8735   3.680 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.233           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.576           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.971           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.907           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.038           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.038           ms/op

Benchmark result is saved to 1712968314560.json
