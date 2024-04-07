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
# Warmup Iteration   1: 1.514 ops/ms
Iteration   1: 6.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.886 ops/ms


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
# Warmup Iteration   1: 5.705 ops/ms
Iteration   1: 11.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.438 ops/ms


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
# Warmup Iteration   1: 4.720 ops/ms
Iteration   1: 11.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.888 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.431 ops/ms
Iteration   1: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.529 ops/ms


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
# Warmup Iteration   1: 4.292 ±(99.9%) 0.079 ms/op
Iteration   1: 2.582 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.582 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.620 ±(99.9%) 0.077 ms/op
Iteration   1: 1.855 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.855 ms/op


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.072 ms/op
Iteration   1: 2.077 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.077 ms/op


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
# Warmup Iteration   1: 4.580 ±(99.9%) 0.114 ms/op
Iteration   1: 3.505 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.505 ms/op


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
# Warmup Iteration   1: 3.470 ±(99.9%) 0.089 ms/op
Iteration   1: 2.267 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.291 ms/op
                 createUser·p0.50:   1.989 ms/op
                 createUser·p0.90:   2.814 ms/op
                 createUser·p0.95:   3.353 ms/op
                 createUser·p0.99:   8.271 ms/op
                 createUser·p0.999:  27.045 ms/op
                 createUser·p0.9999: 30.600 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14329
  mean =      2.267 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11597 
    [ 2.500,  5.000) = 2276 
    [ 5.000,  7.500) = 258 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.353 ms/op
     p(99.0000) =      8.271 ms/op
     p(99.9000) =     27.045 ms/op
     p(99.9900) =     30.600 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 2.973 ±(99.9%) 0.069 ms/op
Iteration   1: 1.833 ±(99.9%) 0.059 ms/op
                 existUser·p0.00:   0.334 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   2.042 ms/op
                 existUser·p0.95:   2.289 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  46.137 ms/op
                 existUser·p0.9999: 46.989 ms/op
                 existUser·p1.00:   46.989 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17443
  mean =      1.833 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 17260 
    [ 5.000, 10.000) = 83 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      2.042 ms/op
     p(95.0000) =      2.289 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     46.137 ms/op
     p(99.9900) =     46.989 ms/op
     p(99.9990) =     46.989 ms/op
     p(99.9999) =     46.989 ms/op
    p(100.0000) =     46.989 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.079 ms/op
Iteration   1: 1.999 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.437 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.634 ms/op
                 getUser·p0.99:   3.404 ms/op
                 getUser·p0.999:  14.074 ms/op
                 getUser·p0.9999: 14.900 ms/op
                 getUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15992
  mean =      1.999 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 365 
    [ 1.250,  2.500) = 14252 
    [ 2.500,  3.750) = 1261 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      3.404 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     14.900 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.127 ms/op
Iteration   1: 3.092 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.247 ms/op
                 listUser·p0.999:  6.591 ms/op
                 listUser·p0.9999: 8.032 ms/op
                 listUser·p1.00:   8.061 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10347
  mean =      3.092 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 32 
    [2.000, 2.500) = 613 
    [2.500, 3.000) = 5384 
    [3.000, 3.500) = 2160 
    [3.500, 4.000) = 1372 
    [4.000, 4.500) = 445 
    [4.500, 5.000) = 190 
    [5.000, 5.500) = 57 
    [5.500, 6.000) = 37 
    [6.000, 6.500) = 35 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.247 ms/op
     p(99.9000) =      6.591 ms/op
     p(99.9900) =      8.032 ms/op
     p(99.9990) =      8.061 ms/op
     p(99.9999) =      8.061 ms/op
    p(100.0000) =      8.061 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.886          ops/ms
ClientSimple.existUser                       thrpt         11.438          ops/ms
ClientSimple.getUser                         thrpt         11.888          ops/ms
ClientSimple.listUser                        thrpt          8.529          ops/ms
ClientSimple.createUser                       avgt          2.582           ms/op
ClientSimple.existUser                        avgt          1.855           ms/op
ClientSimple.getUser                          avgt          2.077           ms/op
ClientSimple.listUser                         avgt          3.505           ms/op
ClientSimple.createUser                     sample  14329   2.267 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.291           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.989           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.353           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.271           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.045           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.600           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.671           ms/op
ClientSimple.existUser                      sample  17443   1.833 ± 0.059   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.334           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.597           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.042           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.289           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.210           ms/op
ClientSimple.existUser:existUser·p0.999     sample         46.137           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         46.989           ms/op
ClientSimple.existUser:existUser·p1.00      sample         46.989           ms/op
ClientSimple.getUser                        sample  15992   1.999 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.437           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.404           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.074           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.900           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.909           ms/op
ClientSimple.listUser                       sample  10347   3.092 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.886           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.916           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.883           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.247           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.591           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.032           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.061           ms/op

Benchmark result is saved to 1712470208816.json
