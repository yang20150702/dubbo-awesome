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
# Warmup Iteration   1: 1.771 ops/ms
Iteration   1: 6.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.808 ops/ms


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
# Warmup Iteration   1: 5.172 ops/ms
Iteration   1: 10.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.282 ops/ms


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
# Warmup Iteration   1: 5.063 ops/ms
Iteration   1: 11.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.982 ops/ms


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
# Warmup Iteration   1: 4.148 ops/ms
Iteration   1: 8.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.145 ops/ms


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.063 ms/op
Iteration   1: 2.165 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.165 ms/op


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
# Warmup Iteration   1: 3.336 ±(99.9%) 0.061 ms/op
Iteration   1: 1.876 ±(99.9%) 0.012 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.071 ms/op
Iteration   1: 1.914 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.914 ms/op


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.099 ms/op
Iteration   1: 3.676 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.676 ms/op


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.094 ms/op
Iteration   1: 2.180 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   1.903 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.897 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  26.268 ms/op
                 createUser·p0.9999: 28.877 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14674
  mean =      2.180 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12361 
    [ 2.500,  5.000) = 2075 
    [ 5.000,  7.500) = 93 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.897 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     26.268 ms/op
     p(99.9900) =     28.877 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.076 ms/op
Iteration   1: 1.905 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.268 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   4.998 ms/op
                 existUser·p0.999:  16.417 ms/op
                 existUser·p0.9999: 16.644 ms/op
                 existUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16789
  mean =      1.905 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 421 
    [ 1.250,  2.500) = 15118 
    [ 2.500,  3.750) = 1020 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.268 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      4.998 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     16.644 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.364 ±(99.9%) 0.094 ms/op
Iteration   1: 2.321 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   2.204 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   2.961 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  14.893 ms/op
                 getUser·p0.9999: 15.133 ms/op
                 getUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13786
  mean =      2.321 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 10020 
    [ 2.500,  3.750) = 3322 
    [ 3.750,  5.000) = 167 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     15.133 ms/op
     p(99.9990) =     15.139 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 4.506 ±(99.9%) 0.148 ms/op
Iteration   1: 3.353 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   3.420 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  8.147 ms/op
                 listUser·p0.9999: 9.257 ms/op
                 listUser·p1.00:   9.257 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9532
  mean =      3.353 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 1 
    [ 1.500,  2.000) = 132 
    [ 2.000,  2.500) = 1336 
    [ 2.500,  3.000) = 1275 
    [ 3.000,  3.500) = 2552 
    [ 3.500,  4.000) = 2985 
    [ 4.000,  4.500) = 981 
    [ 4.500,  5.000) = 138 
    [ 5.000,  5.500) = 28 
    [ 5.500,  6.000) = 29 
    [ 6.000,  6.500) = 16 
    [ 6.500,  7.000) = 23 
    [ 7.000,  7.500) = 7 
    [ 7.500,  8.000) = 6 
    [ 8.000,  8.500) = 19 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      8.147 ms/op
     p(99.9900) =      9.257 ms/op
     p(99.9990) =      9.257 ms/op
     p(99.9999) =      9.257 ms/op
    p(100.0000) =      9.257 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.808          ops/ms
ClientSimple.existUser                       thrpt         10.282          ops/ms
ClientSimple.getUser                         thrpt         11.982          ops/ms
ClientSimple.listUser                        thrpt          8.145          ops/ms
ClientSimple.createUser                       avgt          2.165           ms/op
ClientSimple.existUser                        avgt          1.876           ms/op
ClientSimple.getUser                          avgt          1.914           ms/op
ClientSimple.listUser                         avgt          3.676           ms/op
ClientSimple.createUser                     sample  14674   2.180 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.778           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.903           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.897           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.479           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.268           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.877           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.000           ms/op
ClientSimple.existUser                      sample  16789   1.905 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.268           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.751           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.998           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.417           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.644           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.744           ms/op
ClientSimple.getUser                        sample  13786   2.321 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.510           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.204           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.961           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.923           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.893           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.133           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.139           ms/op
ClientSimple.listUser                       sample   9532   3.353 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.454           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.420           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.104           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.677           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.147           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.257           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.257           ms/op

Benchmark result is saved to 1713377479412.json
