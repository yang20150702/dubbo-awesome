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
# Warmup Iteration   1: 1.790 ops/ms
Iteration   1: 7.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.513 ops/ms


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
# Warmup Iteration   1: 7.142 ops/ms
Iteration   1: 12.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.234 ops/ms


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
# Warmup Iteration   1: 5.859 ops/ms
Iteration   1: 13.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.660 ops/ms


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
# Warmup Iteration   1: 4.369 ops/ms
Iteration   1: 8.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.460 ops/ms


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.081 ms/op
Iteration   1: 2.042 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.042 ms/op


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
# Warmup Iteration   1: 3.092 ±(99.9%) 0.052 ms/op
Iteration   1: 1.803 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.803 ms/op


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
# Warmup Iteration   1: 3.133 ±(99.9%) 0.069 ms/op
Iteration   1: 1.866 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.866 ms/op


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.082 ms/op
Iteration   1: 3.160 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.160 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.080 ms/op
Iteration   1: 1.960 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.401 ms/op
                 createUser·p0.50:   1.759 ms/op
                 createUser·p0.90:   2.261 ms/op
                 createUser·p0.95:   2.490 ms/op
                 createUser·p0.99:   9.146 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 25.361 ms/op
                 createUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16323
  mean =      1.960 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15539 
    [ 2.500,  5.000) = 589 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      9.146 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     25.361 ms/op
     p(99.9990) =     26.149 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 2.941 ±(99.9%) 0.071 ms/op
Iteration   1: 1.817 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.227 ms/op
                 existUser·p0.50:   1.724 ms/op
                 existUser·p0.90:   2.163 ms/op
                 existUser·p0.95:   2.269 ms/op
                 existUser·p0.99:   2.963 ms/op
                 existUser·p0.999:  24.576 ms/op
                 existUser·p0.9999: 25.335 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17649
  mean =      1.817 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17309 
    [ 2.500,  5.000) = 263 
    [ 5.000,  7.500) = 13 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.227 ms/op
     p(50.0000) =      1.724 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.269 ms/op
     p(99.0000) =      2.963 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     25.335 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.077 ms/op
Iteration   1: 2.164 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.114 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.847 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  12.852 ms/op
                 getUser·p0.9999: 13.142 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14778
  mean =      2.164 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 194 
    [ 1.250,  2.500) = 11987 
    [ 2.500,  3.750) = 2372 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =     12.852 ms/op
     p(99.9900) =     13.142 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.134 ms/op
Iteration   1: 2.980 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   2.773 ms/op
                 listUser·p0.90:   3.699 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  12.391 ms/op
                 listUser·p0.9999: 13.990 ms/op
                 listUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10730
  mean =      2.980 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 867 
    [ 2.500,  3.750) = 8849 
    [ 3.750,  5.000) = 835 
    [ 5.000,  6.250) = 132 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     12.391 ms/op
     p(99.9900) =     13.990 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.513          ops/ms
ClientSimple.existUser                       thrpt         12.234          ops/ms
ClientSimple.getUser                         thrpt         13.660          ops/ms
ClientSimple.listUser                        thrpt          8.460          ops/ms
ClientSimple.createUser                       avgt          2.042           ms/op
ClientSimple.existUser                        avgt          1.803           ms/op
ClientSimple.getUser                          avgt          1.866           ms/op
ClientSimple.listUser                         avgt          3.160           ms/op
ClientSimple.createUser                     sample  16323   1.960 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.401           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.759           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.261           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.490           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.146           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.350           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.361           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.149           ms/op
ClientSimple.existUser                      sample  17649   1.817 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.227           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.724           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.163           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.963           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.576           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.335           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.461           ms/op
ClientSimple.getUser                        sample  14778   2.164 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.797           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.114           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.174           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.852           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.142           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample  10730   2.980 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.053           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.773           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.699           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.374           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.391           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.990           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.008           ms/op

Benchmark result is saved to 1711606277797.json
