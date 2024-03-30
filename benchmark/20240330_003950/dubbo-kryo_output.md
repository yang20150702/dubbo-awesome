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
# Warmup Iteration   1: 1.964 ops/ms
Iteration   1: 6.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.143 ops/ms


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
# Warmup Iteration   1: 6.466 ops/ms
Iteration   1: 11.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.948 ops/ms


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
# Warmup Iteration   1: 5.976 ops/ms
Iteration   1: 12.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.548 ops/ms


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
# Warmup Iteration   1: 5.362 ops/ms
Iteration   1: 9.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.063 ops/ms


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.086 ms/op
Iteration   1: 2.121 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.121 ms/op


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
# Warmup Iteration   1: 2.928 ±(99.9%) 0.044 ms/op
Iteration   1: 2.296 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.296 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.081 ms/op
Iteration   1: 1.841 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.841 ms/op


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.100 ms/op
Iteration   1: 3.259 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.259 ms/op


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.107 ms/op
Iteration   1: 2.406 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.273 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.462 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 19.760 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13281
  mean =      2.406 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 8035 
    [ 2.500,  3.750) = 4968 
    [ 3.750,  5.000) = 135 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.273 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.318 ms/op
     p(99.0000) =      4.462 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     19.760 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.082 ms/op
Iteration   1: 1.965 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.303 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  25.049 ms/op
                 existUser·p0.9999: 25.387 ms/op
                 existUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16277
  mean =      1.965 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15132 
    [ 2.500,  5.000) = 1005 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.303 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =     25.049 ms/op
     p(99.9900) =     25.387 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.083 ms/op
Iteration   1: 1.906 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.375 ms/op
                 getUser·p0.50:   1.790 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.540 ms/op
                 getUser·p0.99:   5.114 ms/op
                 getUser·p0.999:  12.780 ms/op
                 getUser·p0.9999: 13.009 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16776
  mean =      1.906 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 335 
    [ 1.250,  2.500) = 15500 
    [ 2.500,  3.750) = 694 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      5.114 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.174 ms/op
Iteration   1: 3.176 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.944 ms/op
                 listUser·p0.9999: 11.082 ms/op
                 listUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10088
  mean =      3.176 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 843 
    [ 2.500,  3.750) = 7676 
    [ 3.750,  5.000) = 1297 
    [ 5.000,  6.250) = 184 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.944 ms/op
     p(99.9900) =     11.082 ms/op
     p(99.9990) =     11.092 ms/op
     p(99.9999) =     11.092 ms/op
    p(100.0000) =     11.092 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.143          ops/ms
ClientSimple.existUser                       thrpt         11.948          ops/ms
ClientSimple.getUser                         thrpt         12.548          ops/ms
ClientSimple.listUser                        thrpt          9.063          ops/ms
ClientSimple.createUser                       avgt          2.121           ms/op
ClientSimple.existUser                        avgt          2.296           ms/op
ClientSimple.getUser                          avgt          1.841           ms/op
ClientSimple.listUser                         avgt          3.259           ms/op
ClientSimple.createUser                     sample  13281   2.406 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.876           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.273           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.125           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.318           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.462           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.055           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.760           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.825           ms/op
ClientSimple.existUser                      sample  16277   1.965 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.303           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.806           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.235           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.049           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.387           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.428           ms/op
ClientSimple.getUser                        sample  16776   1.906 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.375           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.790           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.114           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.780           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.009           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.009           ms/op
ClientSimple.listUser                       sample  10088   3.176 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.083           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.966           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.018           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.628           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.944           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.082           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.092           ms/op

Benchmark result is saved to 1711758940577.json
