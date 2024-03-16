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
# Warmup Iteration   1: 1.736 ops/ms
Iteration   1: 7.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.328 ops/ms


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
# Warmup Iteration   1: 6.175 ops/ms
Iteration   1: 14.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.290 ops/ms


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
# Warmup Iteration   1: 5.515 ops/ms
Iteration   1: 12.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.817 ops/ms


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
# Warmup Iteration   1: 5.276 ops/ms
Iteration   1: 8.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.929 ops/ms


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.077 ms/op
Iteration   1: 2.039 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.039 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.074 ms/op
Iteration   1: 1.775 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.775 ms/op


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
# Warmup Iteration   1: 3.457 ±(99.9%) 0.060 ms/op
Iteration   1: 1.999 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.999 ms/op


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
# Warmup Iteration   1: 4.779 ±(99.9%) 0.114 ms/op
Iteration   1: 3.327 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.327 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.075 ms/op
Iteration   1: 1.901 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   1.757 ms/op
                 createUser·p0.90:   2.179 ms/op
                 createUser·p0.95:   2.393 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 15.323 ms/op
                 createUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17614
  mean =      1.901 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 16704 
    [ 2.500,  3.750) = 428 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.393 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     15.323 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 2.950 ±(99.9%) 0.067 ms/op
Iteration   1: 1.641 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   1.518 ms/op
                 existUser·p0.90:   1.976 ms/op
                 existUser·p0.95:   2.126 ms/op
                 existUser·p0.99:   2.949 ms/op
                 existUser·p0.999:  26.854 ms/op
                 existUser·p0.9999: 27.370 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19474
  mean =      1.641 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19166 
    [ 2.500,  5.000) = 234 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.518 ms/op
     p(90.0000) =      1.976 ms/op
     p(95.0000) =      2.126 ms/op
     p(99.0000) =      2.949 ms/op
     p(99.9000) =     26.854 ms/op
     p(99.9900) =     27.370 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 3.059 ±(99.9%) 0.073 ms/op
Iteration   1: 2.099 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   1.987 ms/op
                 getUser·p0.90:   2.650 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  18.255 ms/op
                 getUser·p0.9999: 19.102 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15224
  mean =      2.099 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 12153 
    [ 2.500,  3.750) = 2650 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =     18.255 ms/op
     p(99.9900) =     19.102 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.393 ±(99.9%) 0.134 ms/op
Iteration   1: 3.336 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.277 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.700 ms/op
                 listUser·p0.999:  7.389 ms/op
                 listUser·p0.9999: 10.404 ms/op
                 listUser·p1.00:   10.404 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9613
  mean =      3.336 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 59 
    [ 2.000,  3.000) = 3512 
    [ 3.000,  4.000) = 4681 
    [ 4.000,  5.000) = 1233 
    [ 5.000,  6.000) = 48 
    [ 6.000,  7.000) = 61 
    [ 7.000,  8.000) = 17 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.700 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     10.404 ms/op
     p(99.9990) =     10.404 ms/op
     p(99.9999) =     10.404 ms/op
    p(100.0000) =     10.404 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.328          ops/ms
ClientSimple.existUser                       thrpt         14.290          ops/ms
ClientSimple.getUser                         thrpt         12.817          ops/ms
ClientSimple.listUser                        thrpt          8.929          ops/ms
ClientSimple.createUser                       avgt          2.039           ms/op
ClientSimple.existUser                        avgt          1.775           ms/op
ClientSimple.getUser                          avgt          1.999           ms/op
ClientSimple.listUser                         avgt          3.327           ms/op
ClientSimple.createUser                     sample  17614   1.901 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.549           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.757           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.179           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.393           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.177           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.762           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.323           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.335           ms/op
ClientSimple.existUser                      sample  19474   1.641 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.450           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.518           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.976           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.949           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.854           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.370           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.525           ms/op
ClientSimple.getUser                        sample  15224   2.099 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.532           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.987           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.067           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.255           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.102           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.137           ms/op
ClientSimple.listUser                       sample   9613   3.336 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.292           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.277           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.104           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.700           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.389           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.404           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.404           ms/op

Benchmark result is saved to 1710569431336.json
