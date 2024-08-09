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
# Warmup Iteration   1: 1.937 ops/ms
Iteration   1: 8.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.275 ops/ms


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
# Warmup Iteration   1: 5.619 ops/ms
Iteration   1: 11.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.132 ops/ms


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
# Warmup Iteration   1: 5.926 ops/ms
Iteration   1: 11.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.565 ops/ms


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
# Warmup Iteration   1: 5.389 ops/ms
Iteration   1: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.704 ops/ms


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.064 ms/op
Iteration   1: 2.108 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.108 ms/op


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
# Warmup Iteration   1: 3.385 ±(99.9%) 0.050 ms/op
Iteration   1: 1.797 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.797 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.053 ms/op
Iteration   1: 1.893 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.085 ms/op
Iteration   1: 3.692 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.692 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.101 ms/op
Iteration   1: 2.258 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   8.741 ms/op
                 createUser·p0.999:  17.067 ms/op
                 createUser·p0.9999: 19.888 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14151
  mean =      2.258 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 11856 
    [ 2.500,  3.750) = 1875 
    [ 3.750,  5.000) = 149 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      8.741 ms/op
     p(99.9000) =     17.067 ms/op
     p(99.9900) =     19.888 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.079 ms/op
Iteration   1: 2.035 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   5.307 ms/op
                 existUser·p0.999:  13.353 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15720
  mean =      2.035 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 13448 
    [ 2.500,  3.750) = 1907 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      5.307 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.085 ms/op
Iteration   1: 2.125 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   2.025 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.908 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  11.993 ms/op
                 getUser·p0.9999: 12.717 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15371
  mean =      2.125 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 12805 
    [ 2.500,  3.750) = 2306 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     12.717 ms/op
     p(99.9990) =     12.796 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.139 ms/op
Iteration   1: 3.410 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.303 ms/op
                 listUser·p0.999:  6.504 ms/op
                 listUser·p0.9999: 7.381 ms/op
                 listUser·p1.00:   7.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9391
  mean =      3.410 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 95 
    [2.000, 2.500) = 740 
    [2.500, 3.000) = 1294 
    [3.000, 3.500) = 2780 
    [3.500, 4.000) = 3322 
    [4.000, 4.500) = 856 
    [4.500, 5.000) = 153 
    [5.000, 5.500) = 61 
    [5.500, 6.000) = 38 
    [6.000, 6.500) = 29 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.303 ms/op
     p(99.9000) =      6.504 ms/op
     p(99.9900) =      7.381 ms/op
     p(99.9990) =      7.381 ms/op
     p(99.9999) =      7.381 ms/op
    p(100.0000) =      7.381 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.275          ops/ms
ClientSimple.existUser                       thrpt         11.132          ops/ms
ClientSimple.getUser                         thrpt         11.565          ops/ms
ClientSimple.listUser                        thrpt          9.704          ops/ms
ClientSimple.createUser                       avgt          2.108           ms/op
ClientSimple.existUser                        avgt          1.797           ms/op
ClientSimple.getUser                          avgt          1.893           ms/op
ClientSimple.listUser                         avgt          3.692           ms/op
ClientSimple.createUser                     sample  14151   2.258 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.811           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.236           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.741           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.067           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.888           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.956           ms/op
ClientSimple.existUser                      sample  15720   2.035 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.514           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.876           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.307           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.353           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.910           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.910           ms/op
ClientSimple.getUser                        sample  15371   2.125 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.730           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.025           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.908           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.777           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.993           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.717           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.796           ms/op
ClientSimple.listUser                       sample   9391   3.410 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.180           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.063           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.303           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.504           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.381           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.381           ms/op

Benchmark result is saved to 1723227170269.json
