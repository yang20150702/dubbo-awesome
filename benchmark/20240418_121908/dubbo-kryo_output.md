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
# Warmup Iteration   1: 1.912 ops/ms
Iteration   1: 7.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.098 ops/ms


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
# Warmup Iteration   1: 6.294 ops/ms
Iteration   1: 11.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.972 ops/ms


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
# Warmup Iteration   1: 5.347 ops/ms
Iteration   1: 13.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.613 ops/ms


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
# Warmup Iteration   1: 5.206 ops/ms
Iteration   1: 8.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.802 ops/ms


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
# Warmup Iteration   1: 3.647 ±(99.9%) 0.080 ms/op
Iteration   1: 2.185 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.185 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.053 ms/op
Iteration   1: 1.948 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.948 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.056 ms/op
Iteration   1: 2.219 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.219 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.092 ms/op
Iteration   1: 3.342 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.342 ms/op


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.118 ms/op
Iteration   1: 2.046 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   1.864 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.818 ms/op
                 createUser·p0.99:   8.036 ms/op
                 createUser·p0.999:  16.401 ms/op
                 createUser·p0.9999: 16.725 ms/op
                 createUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15931
  mean =      2.046 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 14001 
    [ 2.500,  3.750) = 1443 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     16.401 ms/op
     p(99.9900) =     16.725 ms/op
     p(99.9990) =     16.744 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.032 ±(99.9%) 0.067 ms/op
Iteration   1: 1.769 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   1.630 ms/op
                 existUser·p0.90:   2.109 ms/op
                 existUser·p0.95:   2.277 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  26.274 ms/op
                 existUser·p0.9999: 27.091 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18082
  mean =      1.769 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17662 
    [ 2.500,  5.000) = 302 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.630 ms/op
     p(90.0000) =      2.109 ms/op
     p(95.0000) =      2.277 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =     26.274 ms/op
     p(99.9900) =     27.091 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.075 ms/op
Iteration   1: 1.891 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   1.765 ms/op
                 getUser·p0.90:   2.302 ms/op
                 getUser·p0.95:   2.458 ms/op
                 getUser·p0.99:   3.857 ms/op
                 getUser·p0.999:  10.060 ms/op
                 getUser·p0.9999: 10.238 ms/op
                 getUser·p1.00:   10.306 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16909
  mean =      1.891 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 12 
    [ 1.000,  2.000) = 13028 
    [ 2.000,  3.000) = 3551 
    [ 3.000,  4.000) = 151 
    [ 4.000,  5.000) = 41 
    [ 5.000,  6.000) = 87 
    [ 6.000,  7.000) = 4 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.857 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     10.238 ms/op
     p(99.9990) =     10.306 ms/op
     p(99.9999) =     10.306 ms/op
    p(100.0000) =     10.306 ms/op


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.123 ms/op
Iteration   1: 3.715 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.626 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.700 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8609
  mean =      3.715 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 931 
    [ 2.500,  3.750) = 3774 
    [ 3.750,  5.000) = 3495 
    [ 5.000,  6.250) = 268 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.700 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.098          ops/ms
ClientSimple.existUser                       thrpt         11.972          ops/ms
ClientSimple.getUser                         thrpt         13.613          ops/ms
ClientSimple.listUser                        thrpt          8.802          ops/ms
ClientSimple.createUser                       avgt          2.185           ms/op
ClientSimple.existUser                        avgt          1.948           ms/op
ClientSimple.getUser                          avgt          2.219           ms/op
ClientSimple.listUser                         avgt          3.342           ms/op
ClientSimple.createUser                     sample  15931   2.046 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.700           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.864           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.036           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.401           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.725           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.744           ms/op
ClientSimple.existUser                      sample  18082   1.769 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.624           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.630           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.109           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.125           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.274           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.091           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.197           ms/op
ClientSimple.getUser                        sample  16909   1.891 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.918           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.765           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.302           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.857           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.060           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.238           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.306           ms/op
ClientSimple.listUser                       sample   8609   3.715 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.626           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.670           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.700           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.647           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.908           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.908           ms/op

Benchmark result is saved to 1713442474673.json
