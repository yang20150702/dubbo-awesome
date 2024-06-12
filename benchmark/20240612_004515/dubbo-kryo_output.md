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
# Warmup Iteration   1: 1.760 ops/ms
Iteration   1: 6.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.401 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.958 ops/ms
Iteration   1: 12.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.692 ops/ms


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
# Warmup Iteration   1: 5.285 ops/ms
Iteration   1: 12.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.546 ops/ms


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
# Warmup Iteration   1: 3.711 ops/ms
Iteration   1: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.615 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.080 ms/op
Iteration   1: 2.308 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.308 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ±(99.9%) 0.064 ms/op
Iteration   1: 1.661 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.661 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.428 ±(99.9%) 0.061 ms/op
Iteration   1: 2.098 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.098 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.379 ±(99.9%) 0.093 ms/op
Iteration   1: 3.182 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.182 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ±(99.9%) 0.102 ms/op
Iteration   1: 2.096 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.383 ms/op
                 createUser·p0.50:   1.915 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.896 ms/op
                 createUser·p0.99:   11.207 ms/op
                 createUser·p0.999:  15.729 ms/op
                 createUser·p0.9999: 16.394 ms/op
                 createUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15240
  mean =      2.096 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 382 
    [ 1.250,  2.500) = 12713 
    [ 2.500,  3.750) = 1890 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     16.394 ms/op
     p(99.9990) =     16.531 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.911 ±(99.9%) 0.069 ms/op
Iteration   1: 2.053 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   1.868 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.969 ms/op
                 existUser·p0.999:  27.361 ms/op
                 existUser·p0.9999: 28.058 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15743
  mean =      2.053 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14128 
    [ 2.500,  5.000) = 1513 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =     27.361 ms/op
     p(99.9900) =     28.058 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 3.440 ±(99.9%) 0.103 ms/op
Iteration   1: 2.115 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   1.989 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   2.833 ms/op
                 getUser·p0.99:   3.443 ms/op
                 getUser·p0.999:  13.074 ms/op
                 getUser·p0.9999: 13.834 ms/op
                 getUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15145
  mean =      2.115 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 12517 
    [ 2.500,  3.750) = 2435 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.833 ms/op
     p(99.0000) =      3.443 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     13.834 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.113 ms/op
Iteration   1: 3.177 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 13.615 ms/op
                 listUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10059
  mean =      3.177 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1395 
    [ 2.500,  3.750) = 6789 
    [ 3.750,  5.000) = 1671 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.401          ops/ms
ClientSimple.existUser                       thrpt         12.692          ops/ms
ClientSimple.getUser                         thrpt         12.546          ops/ms
ClientSimple.listUser                        thrpt          8.615          ops/ms
ClientSimple.createUser                       avgt          2.308           ms/op
ClientSimple.existUser                        avgt          1.661           ms/op
ClientSimple.getUser                          avgt          2.098           ms/op
ClientSimple.listUser                         avgt          3.182           ms/op
ClientSimple.createUser                     sample  15240   2.096 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.383           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.915           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.896           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.207           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.729           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.394           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.531           ms/op
ClientSimple.existUser                      sample  15743   2.053 ± 0.042   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.515           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.868           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.969           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.361           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.058           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.115           ms/op
ClientSimple.getUser                        sample  15145   2.115 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.671           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.989           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.833           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.443           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.074           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.834           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.205           ms/op
ClientSimple.listUser                       sample  10059   3.177 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.214           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.941           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.406           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.500           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.615           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.615           ms/op

Benchmark result is saved to 1718152862890.json
