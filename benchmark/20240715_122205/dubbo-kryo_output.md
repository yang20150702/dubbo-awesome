# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.938 ops/ms
Iteration   1: 7.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.147 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.978 ops/ms
Iteration   1: 12.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.802 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.049 ops/ms
Iteration   1: 15.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.850 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.014 ops/ms
Iteration   1: 8.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.083 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.540 ±(99.9%) 0.059 ms/op
Iteration   1: 1.999 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.109 ±(99.9%) 0.044 ms/op
Iteration   1: 1.943 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.182 ±(99.9%) 0.064 ms/op
Iteration   1: 1.991 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.991 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.424 ±(99.9%) 0.074 ms/op
Iteration   1: 3.533 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ±(99.9%) 0.120 ms/op
Iteration   1: 2.323 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.138 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.404 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  12.096 ms/op
                 createUser·p0.9999: 12.314 ms/op
                 createUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13869
  mean =      2.323 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 10018 
    [ 2.500,  3.750) = 3287 
    [ 3.750,  5.000) = 352 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.404 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     12.096 ms/op
     p(99.9900) =     12.314 ms/op
     p(99.9990) =     12.321 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.042 ±(99.9%) 0.076 ms/op
Iteration   1: 2.187 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.187 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   3.189 ms/op
                 existUser·p0.999:  16.241 ms/op
                 existUser·p0.9999: 16.482 ms/op
                 existUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14705
  mean =      2.187 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 268 
    [ 1.250,  2.500) = 12412 
    [ 2.500,  3.750) = 1929 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.189 ms/op
     p(99.9000) =     16.241 ms/op
     p(99.9900) =     16.482 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.413 ±(99.9%) 0.084 ms/op
Iteration   1: 1.983 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   1.868 ms/op
                 getUser·p0.90:   2.458 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.371 ms/op
                 getUser·p0.999:  11.239 ms/op
                 getUser·p0.9999: 11.512 ms/op
                 getUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16148
  mean =      1.983 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 14711 
    [ 2.500,  3.750) = 1299 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.371 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     11.512 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.633 ms/op
    p(100.0000) =     11.633 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.236 ±(99.9%) 0.137 ms/op
Iteration   1: 3.709 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  7.497 ms/op
                 listUser·p0.9999: 11.502 ms/op
                 listUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8610
  mean =      3.709 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 854 
    [ 2.500,  3.750) = 3248 
    [ 3.750,  5.000) = 4146 
    [ 5.000,  6.250) = 253 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =      7.497 ms/op
     p(99.9900) =     11.502 ms/op
     p(99.9990) =     11.502 ms/op
     p(99.9999) =     11.502 ms/op
    p(100.0000) =     11.502 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.147          ops/ms
ClientSimple.existUser                       thrpt         12.802          ops/ms
ClientSimple.getUser                         thrpt         15.850          ops/ms
ClientSimple.listUser                        thrpt          8.083          ops/ms
ClientSimple.createUser                       avgt          1.999           ms/op
ClientSimple.existUser                        avgt          1.943           ms/op
ClientSimple.getUser                          avgt          1.991           ms/op
ClientSimple.listUser                         avgt          3.533           ms/op
ClientSimple.createUser                     sample  13869   2.323 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.676           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.138           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.990           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.404           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.128           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.096           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.314           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.321           ms/op
ClientSimple.existUser                      sample  14705   2.187 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.653           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.187           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.189           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.241           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.482           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.482           ms/op
ClientSimple.getUser                        sample  16148   1.983 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.756           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.868           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.371           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.239           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.512           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.633           ms/op
ClientSimple.listUser                       sample   8610   3.709 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.948           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.785           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.891           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.406           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.497           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.502           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.502           ms/op

Benchmark result is saved to 1721045879011.json
