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
# Warmup Iteration   1: 2.119 ops/ms
Iteration   1: 6.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.683 ops/ms


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
# Warmup Iteration   1: 5.639 ops/ms
Iteration   1: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.897 ops/ms


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
# Warmup Iteration   1: 6.130 ops/ms
Iteration   1: 13.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.123 ops/ms


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
# Warmup Iteration   1: 4.886 ops/ms
Iteration   1: 7.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.876 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.075 ms/op
Iteration   1: 2.213 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.213 ms/op


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.059 ms/op
Iteration   1: 1.717 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.717 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.055 ms/op
Iteration   1: 2.363 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.363 ms/op


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.074 ms/op
Iteration   1: 3.425 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.425 ms/op


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
# Warmup Iteration   1: 3.582 ±(99.9%) 0.082 ms/op
Iteration   1: 2.392 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   5.991 ms/op
                 createUser·p0.999:  16.526 ms/op
                 createUser·p0.9999: 17.277 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13362
  mean =      2.392 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 9136 
    [ 2.500,  3.750) = 3796 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 110 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      5.991 ms/op
     p(99.9000) =     16.526 ms/op
     p(99.9900) =     17.277 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.069 ±(99.9%) 0.071 ms/op
Iteration   1: 1.661 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   1.583 ms/op
                 existUser·p0.90:   1.911 ms/op
                 existUser·p0.95:   2.083 ms/op
                 existUser·p0.99:   2.616 ms/op
                 existUser·p0.999:  25.952 ms/op
                 existUser·p0.9999: 26.716 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19234
  mean =      1.661 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18973 
    [ 2.500,  5.000) = 193 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      1.583 ms/op
     p(90.0000) =      1.911 ms/op
     p(95.0000) =      2.083 ms/op
     p(99.0000) =      2.616 ms/op
     p(99.9000) =     25.952 ms/op
     p(99.9900) =     26.716 ms/op
     p(99.9990) =     26.837 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 3.479 ±(99.9%) 0.093 ms/op
Iteration   1: 2.104 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   1.962 ms/op
                 getUser·p0.90:   2.765 ms/op
                 getUser·p0.95:   2.974 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  14.975 ms/op
                 getUser·p0.9999: 15.130 ms/op
                 getUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15220
  mean =      2.104 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 275 
    [ 1.250,  2.500) = 11550 
    [ 2.500,  3.750) = 3136 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 100 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     15.130 ms/op
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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.167 ms/op
Iteration   1: 3.537 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.478 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   8.865 ms/op
                 listUser·p0.999:  20.936 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9040
  mean =      3.537 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1142 
    [ 2.500,  5.000) = 7544 
    [ 5.000,  7.500) = 229 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      8.865 ms/op
     p(99.9000) =     20.936 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.683          ops/ms
ClientSimple.existUser                       thrpt         12.897          ops/ms
ClientSimple.getUser                         thrpt         13.123          ops/ms
ClientSimple.listUser                        thrpt          7.876          ops/ms
ClientSimple.createUser                       avgt          2.213           ms/op
ClientSimple.existUser                        avgt          1.717           ms/op
ClientSimple.getUser                          avgt          2.363           ms/op
ClientSimple.listUser                         avgt          3.425           ms/op
ClientSimple.createUser                     sample  13362   2.392 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.521           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.310           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.991           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.526           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.277           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.629           ms/op
ClientSimple.existUser                      sample  19234   1.661 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.434           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.583           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.911           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.083           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.616           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.952           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.716           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.837           ms/op
ClientSimple.getUser                        sample  15220   2.104 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.579           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.962           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.974           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.841           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.975           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.130           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.139           ms/op
ClientSimple.listUser                       sample   9040   3.537 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.967           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.478           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.865           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.936           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.053           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.053           ms/op

Benchmark result is saved to 1710635981331.json
