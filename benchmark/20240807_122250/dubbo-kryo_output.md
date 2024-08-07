# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.085 ops/ms
Iteration   1: 5.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.826 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.678 ops/ms
Iteration   1: 12.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.191 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.090 ops/ms
Iteration   1: 11.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.426 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.737 ops/ms
Iteration   1: 8.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.435 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.730 ±(99.9%) 0.132 ms/op
Iteration   1: 2.183 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.183 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.317 ±(99.9%) 0.056 ms/op
Iteration   1: 1.929 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.929 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.261 ±(99.9%) 0.050 ms/op
Iteration   1: 2.402 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.906 ±(99.9%) 0.093 ms/op
Iteration   1: 3.476 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.476 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.410 ±(99.9%) 0.091 ms/op
Iteration   1: 2.259 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   2.089 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   6.821 ms/op
                 createUser·p0.999:  23.096 ms/op
                 createUser·p0.9999: 23.533 ms/op
                 createUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14169
  mean =      2.259 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11009 
    [ 2.500,  5.000) = 2963 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      6.821 ms/op
     p(99.9000) =     23.096 ms/op
     p(99.9900) =     23.533 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.962 ±(99.9%) 0.066 ms/op
Iteration   1: 1.644 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   1.458 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.738 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  12.124 ms/op
                 existUser·p0.9999: 12.810 ms/op
                 existUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19590
  mean =      1.644 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2083 
    [ 1.250,  2.500) = 16128 
    [ 2.500,  3.750) = 1249 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.458 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.738 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     12.810 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.293 ±(99.9%) 0.100 ms/op
Iteration   1: 1.904 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   1.802 ms/op
                 getUser·p0.90:   2.421 ms/op
                 getUser·p0.95:   2.662 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  16.876 ms/op
                 getUser·p0.9999: 17.125 ms/op
                 getUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16791
  mean =      1.904 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 477 
    [ 1.250,  2.500) = 14961 
    [ 2.500,  3.750) = 1179 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     17.125 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.057 ±(99.9%) 0.173 ms/op
Iteration   1: 3.357 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.746 ms/op
                 listUser·p0.50:   3.092 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   8.164 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9616
  mean =      3.357 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 1294 
    [ 2.500,  3.750) = 5417 
    [ 3.750,  5.000) = 2617 
    [ 5.000,  6.250) = 124 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      8.164 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.826          ops/ms
ClientSimple.existUser                       thrpt         12.191          ops/ms
ClientSimple.getUser                         thrpt         11.426          ops/ms
ClientSimple.listUser                        thrpt          8.435          ops/ms
ClientSimple.createUser                       avgt          2.183           ms/op
ClientSimple.existUser                        avgt          1.929           ms/op
ClientSimple.getUser                          avgt          2.402           ms/op
ClientSimple.listUser                         avgt          3.476           ms/op
ClientSimple.createUser                     sample  14169   2.259 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.739           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.089           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.113           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.821           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.096           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.533           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.560           ms/op
ClientSimple.existUser                      sample  19590   1.644 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.473           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.458           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.738           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.457           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.124           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.810           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.517           ms/op
ClientSimple.getUser                        sample  16791   1.904 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.663           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.802           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.908           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.876           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.125           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.236           ms/op
ClientSimple.listUser                       sample   9616   3.357 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.746           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.092           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.164           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.514           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.842           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.842           ms/op

Benchmark result is saved to 1723033096660.json
