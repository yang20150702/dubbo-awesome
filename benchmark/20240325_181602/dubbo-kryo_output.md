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
# Warmup Iteration   1: 1.035 ops/ms
Iteration   1: 5.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.206 ops/ms


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
# Warmup Iteration   1: 6.624 ops/ms
Iteration   1: 11.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.596 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.780 ops/ms
Iteration   1: 13.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.098 ops/ms


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
# Warmup Iteration   1: 5.633 ops/ms
Iteration   1: 9.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.065 ops/ms


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.073 ms/op
Iteration   1: 2.175 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.175 ms/op


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
# Warmup Iteration   1: 3.243 ±(99.9%) 0.051 ms/op
Iteration   1: 2.008 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.008 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.051 ms/op
Iteration   1: 1.985 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.985 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.086 ms/op
Iteration   1: 3.332 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.332 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.116 ms/op
Iteration   1: 2.178 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   5.969 ms/op
                 createUser·p0.999:  16.001 ms/op
                 createUser·p0.9999: 20.857 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14670
  mean =      2.178 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12146 
    [ 2.500,  5.000) = 2328 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      5.969 ms/op
     p(99.9000) =     16.001 ms/op
     p(99.9900) =     20.857 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 2.981 ±(99.9%) 0.066 ms/op
Iteration   1: 2.035 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.316 ms/op
                 existUser·p0.50:   1.878 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   5.789 ms/op
                 existUser·p0.999:  31.883 ms/op
                 existUser·p0.9999: 32.358 ms/op
                 existUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15835
  mean =      2.035 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14683 
    [ 2.500,  5.000) = 958 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      5.789 ms/op
     p(99.9000) =     31.883 ms/op
     p(99.9900) =     32.358 ms/op
     p(99.9990) =     32.473 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.099 ms/op
Iteration   1: 2.021 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.544 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   3.429 ms/op
                 getUser·p0.999:  10.419 ms/op
                 getUser·p0.9999: 11.038 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16044
  mean =      2.021 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 14077 
    [ 2.500,  3.750) = 1733 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.429 ms/op
     p(99.9000) =     10.419 ms/op
     p(99.9900) =     11.038 ms/op
     p(99.9990) =     11.207 ms/op
     p(99.9999) =     11.207 ms/op
    p(100.0000) =     11.207 ms/op


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.132 ms/op
Iteration   1: 3.210 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.218 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9950
  mean =      3.210 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1234 
    [ 2.500,  3.750) = 6773 
    [ 3.750,  5.000) = 1795 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.206          ops/ms
ClientSimple.existUser                       thrpt         11.596          ops/ms
ClientSimple.getUser                         thrpt         13.098          ops/ms
ClientSimple.listUser                        thrpt          9.065          ops/ms
ClientSimple.createUser                       avgt          2.175           ms/op
ClientSimple.existUser                        avgt          2.008           ms/op
ClientSimple.getUser                          avgt          1.985           ms/op
ClientSimple.listUser                         avgt          3.332           ms/op
ClientSimple.createUser                     sample  14670   2.178 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.784           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.969           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.001           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.857           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  15835   2.035 ± 0.040   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.316           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.878           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.789           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.883           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.358           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.473           ms/op
ClientSimple.getUser                        sample  16044   2.021 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.598           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.429           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.419           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.038           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.207           ms/op
ClientSimple.listUser                       sample   9950   3.210 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.852           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.957           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.218           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.924           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.711           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.711           ms/op

Benchmark result is saved to 1711390289446.json
