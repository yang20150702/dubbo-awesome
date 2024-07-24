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
# Warmup Iteration   1: 2.219 ops/ms
Iteration   1: 7.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.989 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.208 ops/ms
Iteration   1: 11.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.593 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.584 ops/ms
Iteration   1: 14.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.226 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.895 ops/ms
Iteration   1: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.363 ops/ms


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.075 ms/op
Iteration   1: 2.144 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.144 ms/op


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
# Warmup Iteration   1: 3.411 ±(99.9%) 0.059 ms/op
Iteration   1: 1.952 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.952 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.063 ms/op
Iteration   1: 2.160 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.160 ms/op


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
# Warmup Iteration   1: 5.049 ±(99.9%) 0.101 ms/op
Iteration   1: 3.855 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.855 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.084 ms/op
Iteration   1: 2.074 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.462 ms/op
                 createUser·p0.50:   1.915 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   2.752 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 23.930 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15421
  mean =      2.074 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13412 
    [ 2.500,  5.000) = 1737 
    [ 5.000,  7.500) = 140 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.752 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     23.930 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 2.913 ±(99.9%) 0.057 ms/op
Iteration   1: 1.776 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   3.215 ms/op
                 existUser·p0.999:  15.975 ms/op
                 existUser·p0.9999: 17.380 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17994
  mean =      1.776 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2179 
    [ 1.250,  2.500) = 14338 
    [ 2.500,  3.750) = 1391 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.215 ms/op
     p(99.9000) =     15.975 ms/op
     p(99.9900) =     17.380 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.088 ms/op
Iteration   1: 1.945 ±(99.9%) 0.079 ms/op
                 getUser·p0.00:   0.511 ms/op
                 getUser·p0.50:   1.737 ms/op
                 getUser·p0.90:   2.212 ms/op
                 getUser·p0.95:   2.404 ms/op
                 getUser·p0.99:   3.914 ms/op
                 getUser·p0.999:  68.813 ms/op
                 getUser·p0.9999: 73.316 ms/op
                 getUser·p1.00:   73.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16436
  mean =      1.945 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16320 
    [ 5.000, 10.000) = 52 
    [10.000, 15.000) = 29 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 20 
    [70.000, 75.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      3.914 ms/op
     p(99.9000) =     68.813 ms/op
     p(99.9900) =     73.316 ms/op
     p(99.9990) =     73.400 ms/op
     p(99.9999) =     73.400 ms/op
    p(100.0000) =     73.400 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.136 ms/op
Iteration   1: 3.849 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.838 ms/op
                 listUser·p0.999:  14.555 ms/op
                 listUser·p0.9999: 14.647 ms/op
                 listUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8303
  mean =      3.849 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 167 
    [ 2.500,  3.750) = 3524 
    [ 3.750,  5.000) = 4290 
    [ 5.000,  6.250) = 215 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.838 ms/op
     p(99.9000) =     14.555 ms/op
     p(99.9900) =     14.647 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.989          ops/ms
ClientSimple.existUser                       thrpt         11.593          ops/ms
ClientSimple.getUser                         thrpt         14.226          ops/ms
ClientSimple.listUser                        thrpt          8.363          ops/ms
ClientSimple.createUser                       avgt          2.144           ms/op
ClientSimple.existUser                        avgt          1.952           ms/op
ClientSimple.getUser                          avgt          2.160           ms/op
ClientSimple.listUser                         avgt          3.855           ms/op
ClientSimple.createUser                     sample  15421   2.074 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.462           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.915           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.752           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.832           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.236           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.930           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.019           ms/op
ClientSimple.existUser                      sample  17994   1.776 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.585           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.620           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.215           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.975           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.380           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.564           ms/op
ClientSimple.getUser                        sample  16436   1.945 ± 0.079   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.511           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.737           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.212           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.914           ms/op
ClientSimple.getUser:getUser·p0.999         sample         68.813           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         73.316           ms/op
ClientSimple.getUser:getUser·p1.00          sample         73.400           ms/op
ClientSimple.listUser                       sample   8303   3.849 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.448           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.830           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.838           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.555           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.647           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.647           ms/op

Benchmark result is saved to 1721823406953.json
