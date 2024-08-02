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
# Warmup Iteration   1: 1.894 ops/ms
Iteration   1: 7.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.430 ops/ms


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
# Warmup Iteration   1: 6.013 ops/ms
Iteration   1: 13.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.473 ops/ms


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
# Warmup Iteration   1: 6.006 ops/ms
Iteration   1: 13.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.091 ops/ms


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
# Warmup Iteration   1: 4.839 ops/ms
Iteration   1: 9.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.229 ops/ms


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.072 ms/op
Iteration   1: 2.042 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.042 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.053 ms/op
Iteration   1: 1.972 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.972 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.055 ms/op
Iteration   1: 1.900 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.900 ms/op


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.099 ms/op
Iteration   1: 3.386 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.386 ms/op


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
# Warmup Iteration   1: 3.158 ±(99.9%) 0.087 ms/op
Iteration   1: 2.124 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.821 ms/op
                 createUser·p0.99:   7.049 ms/op
                 createUser·p0.999:  18.938 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15047
  mean =      2.124 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 485 
    [ 1.250,  2.500) = 12759 
    [ 2.500,  3.750) = 1413 
    [ 3.750,  5.000) = 169 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.821 ms/op
     p(99.0000) =      7.049 ms/op
     p(99.9000) =     18.938 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 3.278 ±(99.9%) 0.100 ms/op
Iteration   1: 2.008 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   1.956 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   3.726 ms/op
                 existUser·p0.999:  16.482 ms/op
                 existUser·p0.9999: 17.675 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15912
  mean =      2.008 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 468 
    [ 1.250,  2.500) = 14605 
    [ 2.500,  3.750) = 687 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.726 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     17.675 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.084 ms/op
Iteration   1: 2.025 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   1.925 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.621 ms/op
                 getUser·p0.99:   3.035 ms/op
                 getUser·p0.999:  14.343 ms/op
                 getUser·p0.9999: 14.670 ms/op
                 getUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15785
  mean =      2.025 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 14277 
    [ 2.500,  3.750) = 1345 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.035 ms/op
     p(99.9000) =     14.343 ms/op
     p(99.9900) =     14.670 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.145 ms/op
Iteration   1: 3.350 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.601 ms/op
                 listUser·p0.50:   3.457 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.321 ms/op
                 listUser·p0.999:  6.008 ms/op
                 listUser·p0.9999: 6.291 ms/op
                 listUser·p1.00:   6.291 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9543
  mean =      3.350 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 57 
    [1.500, 2.000) = 242 
    [2.000, 2.500) = 1077 
    [2.500, 3.000) = 1599 
    [3.000, 3.500) = 2053 
    [3.500, 4.000) = 2963 
    [4.000, 4.500) = 1138 
    [4.500, 5.000) = 298 
    [5.000, 5.500) = 45 
    [5.500, 6.000) = 57 
    [6.000, 6.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.321 ms/op
     p(99.9000) =      6.008 ms/op
     p(99.9900) =      6.291 ms/op
     p(99.9990) =      6.291 ms/op
     p(99.9999) =      6.291 ms/op
    p(100.0000) =      6.291 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.430          ops/ms
ClientSimple.existUser                       thrpt         13.473          ops/ms
ClientSimple.getUser                         thrpt         13.091          ops/ms
ClientSimple.listUser                        thrpt          9.229          ops/ms
ClientSimple.createUser                       avgt          2.042           ms/op
ClientSimple.existUser                        avgt          1.972           ms/op
ClientSimple.getUser                          avgt          1.900           ms/op
ClientSimple.listUser                         avgt          3.386           ms/op
ClientSimple.createUser                     sample  15047   2.124 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.562           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.821           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.049           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.938           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.366           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.366           ms/op
ClientSimple.existUser                      sample  15912   2.008 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.538           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.956           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.726           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.482           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.675           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.695           ms/op
ClientSimple.getUser                        sample  15785   2.025 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.575           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.925           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.035           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.343           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.670           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.746           ms/op
ClientSimple.listUser                       sample   9543   3.350 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.601           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.457           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.133           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.321           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.008           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.291           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.291           ms/op

Benchmark result is saved to 1722559372501.json
