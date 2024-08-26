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
# Warmup Iteration   1: 1.724 ops/ms
Iteration   1: 6.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.931 ops/ms


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
# Warmup Iteration   1: 6.306 ops/ms
Iteration   1: 12.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.384 ops/ms


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
# Warmup Iteration   1: 5.224 ops/ms
Iteration   1: 10.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.854 ops/ms


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
# Warmup Iteration   1: 5.004 ops/ms
Iteration   1: 8.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.327 ops/ms


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.066 ms/op
Iteration   1: 2.474 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.474 ms/op


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
# Warmup Iteration   1: 3.634 ±(99.9%) 0.088 ms/op
Iteration   1: 1.925 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.925 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.050 ms/op
Iteration   1: 2.092 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.092 ms/op


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.097 ms/op
Iteration   1: 3.406 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.406 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.099 ms/op
Iteration   1: 2.133 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   1.978 ms/op
                 createUser·p0.90:   2.540 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   5.301 ms/op
                 createUser·p0.999:  14.729 ms/op
                 createUser·p0.9999: 15.287 ms/op
                 createUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14984
  mean =      2.133 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 13248 
    [ 2.500,  3.750) = 1256 
    [ 3.750,  5.000) = 209 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      5.301 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     15.287 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
Iteration   1: 1.749 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   1.640 ms/op
                 existUser·p0.90:   2.068 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   2.913 ms/op
                 existUser·p0.999:  17.007 ms/op
                 existUser·p0.9999: 17.750 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18291
  mean =      1.749 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 351 
    [ 1.250,  2.500) = 17169 
    [ 2.500,  3.750) = 676 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.068 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      2.913 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     17.750 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.125 ms/op
Iteration   1: 1.993 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   1.860 ms/op
                 getUser·p0.90:   2.515 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   3.391 ms/op
                 getUser·p0.999:  13.778 ms/op
                 getUser·p0.9999: 16.660 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16036
  mean =      1.993 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 14287 
    [ 2.500,  3.750) = 1581 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.391 ms/op
     p(99.9000) =     13.778 ms/op
     p(99.9900) =     16.660 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 5.290 ±(99.9%) 0.152 ms/op
Iteration   1: 3.504 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   3.432 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  11.485 ms/op
                 listUser·p0.9999: 12.009 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9121
  mean =      3.504 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 303 
    [ 2.500,  3.750) = 5844 
    [ 3.750,  5.000) = 2561 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     12.009 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.931          ops/ms
ClientSimple.existUser                       thrpt         12.384          ops/ms
ClientSimple.getUser                         thrpt         10.854          ops/ms
ClientSimple.listUser                        thrpt          8.327          ops/ms
ClientSimple.createUser                       avgt          2.474           ms/op
ClientSimple.existUser                        avgt          1.925           ms/op
ClientSimple.getUser                          avgt          2.092           ms/op
ClientSimple.listUser                         avgt          3.406           ms/op
ClientSimple.createUser                     sample  14984   2.133 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.738           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.978           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.301           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.729           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.287           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.516           ms/op
ClientSimple.existUser                      sample  18291   1.749 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.604           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.640           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.068           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.913           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.007           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.750           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.859           ms/op
ClientSimple.getUser                        sample  16036   1.993 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.676           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.860           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.391           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.778           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.660           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.007           ms/op
ClientSimple.listUser                       sample   9121   3.504 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.865           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.432           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.267           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.485           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.009           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.009           ms/op

Benchmark result is saved to 1724633058499.json
