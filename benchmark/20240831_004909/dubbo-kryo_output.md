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
# Warmup Iteration   1: 1.880 ops/ms
Iteration   1: 6.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.825 ops/ms


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
# Warmup Iteration   1: 5.401 ops/ms
Iteration   1: 11.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.170 ops/ms


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
# Warmup Iteration   1: 4.501 ops/ms
Iteration   1: 12.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.041 ops/ms


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
# Warmup Iteration   1: 5.143 ops/ms
Iteration   1: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.343 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.481 ±(99.9%) 0.099 ms/op
Iteration   1: 2.222 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.222 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.059 ms/op
Iteration   1: 2.014 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.014 ms/op


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
# Warmup Iteration   1: 2.969 ±(99.9%) 0.050 ms/op
Iteration   1: 1.749 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.749 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.088 ms/op
Iteration   1: 3.121 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.121 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.095 ms/op
Iteration   1: 2.441 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.929 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   8.666 ms/op
                 createUser·p0.999:  20.049 ms/op
                 createUser·p0.9999: 20.732 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13137
  mean =      2.441 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9489 
    [ 2.500,  5.000) = 3338 
    [ 5.000,  7.500) = 84 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      8.666 ms/op
     p(99.9000) =     20.049 ms/op
     p(99.9900) =     20.732 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 2.845 ±(99.9%) 0.073 ms/op
Iteration   1: 2.096 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.671 ms/op
                 existUser·p0.95:   2.851 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  13.517 ms/op
                 existUser·p0.9999: 14.185 ms/op
                 existUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15366
  mean =      2.096 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 777 
    [ 1.250,  2.500) = 11425 
    [ 2.500,  3.750) = 2868 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     14.185 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.089 ms/op
Iteration   1: 2.201 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   2.038 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  27.901 ms/op
                 getUser·p0.9999: 29.181 ms/op
                 getUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14513
  mean =      2.201 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12942 
    [ 2.500,  5.000) = 1469 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.038 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =     27.901 ms/op
     p(99.9900) =     29.181 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 6.015 ±(99.9%) 0.192 ms/op
Iteration   1: 3.341 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.115 ms/op
                 listUser·p0.9999: 14.713 ms/op
                 listUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9698
  mean =      3.341 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1369 
    [ 2.500,  3.750) = 5477 
    [ 3.750,  5.000) = 2472 
    [ 5.000,  6.250) = 222 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.115 ms/op
     p(99.9900) =     14.713 ms/op
     p(99.9990) =     14.713 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.825          ops/ms
ClientSimple.existUser                       thrpt         11.170          ops/ms
ClientSimple.getUser                         thrpt         12.041          ops/ms
ClientSimple.listUser                        thrpt          8.343          ops/ms
ClientSimple.createUser                       avgt          2.222           ms/op
ClientSimple.existUser                        avgt          2.014           ms/op
ClientSimple.getUser                          avgt          1.749           ms/op
ClientSimple.listUser                         avgt          3.121           ms/op
ClientSimple.createUser                     sample  13137   2.441 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.531           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.330           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.666           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.049           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.732           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.742           ms/op
ClientSimple.existUser                      sample  15366   2.096 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.802           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.851           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.956           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.517           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.185           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.238           ms/op
ClientSimple.getUser                        sample  14513   2.201 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.625           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.038           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.071           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.901           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.181           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.196           ms/op
ClientSimple.listUser                       sample   9698   3.341 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.241           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.988           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.115           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.713           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.713           ms/op

Benchmark result is saved to 1725065103271.json
