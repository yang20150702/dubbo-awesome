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
# Warmup Iteration   1: 1.861 ops/ms
Iteration   1: 6.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.655 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.075 ops/ms
Iteration   1: 12.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.868 ops/ms


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
# Warmup Iteration   1: 6.389 ops/ms
Iteration   1: 13.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.780 ops/ms


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
# Warmup Iteration   1: 5.251 ops/ms
Iteration   1: 7.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.952 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.260 ±(99.9%) 0.083 ms/op
Iteration   1: 1.957 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.957 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.855 ±(99.9%) 0.040 ms/op
Iteration   1: 1.987 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.987 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ±(99.9%) 0.061 ms/op
Iteration   1: 2.174 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.174 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.420 ±(99.9%) 0.094 ms/op
Iteration   1: 3.942 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.942 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.861 ±(99.9%) 0.100 ms/op
Iteration   1: 2.175 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.453 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   2.945 ms/op
                 createUser·p0.99:   4.102 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 18.778 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14762
  mean =      2.175 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 12297 
    [ 2.500,  3.750) = 2193 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.102 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     18.778 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.135 ±(99.9%) 0.079 ms/op
Iteration   1: 1.876 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   1.688 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   5.269 ms/op
                 existUser·p0.999:  16.605 ms/op
                 existUser·p0.9999: 17.175 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17178
  mean =      1.876 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2592 
    [ 1.250,  2.500) = 12299 
    [ 2.500,  3.750) = 2063 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      5.269 ms/op
     p(99.9000) =     16.605 ms/op
     p(99.9900) =     17.175 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.077 ms/op
Iteration   1: 2.191 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.159 ms/op
                 getUser·p0.90:   2.671 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   3.548 ms/op
                 getUser·p0.999:  13.107 ms/op
                 getUser·p0.9999: 13.608 ms/op
                 getUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14590
  mean =      2.191 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 11762 
    [ 2.500,  3.750) = 2610 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      3.548 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     13.608 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 5.336 ±(99.9%) 0.192 ms/op
Iteration   1: 3.242 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.190 ms/op
                 listUser·p0.999:  13.727 ms/op
                 listUser·p0.9999: 14.467 ms/op
                 listUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9861
  mean =      3.242 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 344 
    [ 2.500,  3.750) = 7520 
    [ 3.750,  5.000) = 1785 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.190 ms/op
     p(99.9000) =     13.727 ms/op
     p(99.9900) =     14.467 ms/op
     p(99.9990) =     14.467 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.655          ops/ms
ClientSimple.existUser                       thrpt         12.868          ops/ms
ClientSimple.getUser                         thrpt         13.780          ops/ms
ClientSimple.listUser                        thrpt          7.952          ops/ms
ClientSimple.createUser                       avgt          1.957           ms/op
ClientSimple.existUser                        avgt          1.987           ms/op
ClientSimple.getUser                          avgt          2.174           ms/op
ClientSimple.listUser                         avgt          3.942           ms/op
ClientSimple.createUser                     sample  14762   2.175 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.453           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.945           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.102           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.514           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.778           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.809           ms/op
ClientSimple.existUser                      sample  17178   1.876 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.553           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.688           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.043           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.269           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.605           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.175           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.269           ms/op
ClientSimple.getUser                        sample  14590   2.191 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.763           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.548           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.107           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.608           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.894           ms/op
ClientSimple.listUser                       sample   9861   3.242 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.910           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.941           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.190           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.727           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.467           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.467           ms/op

Benchmark result is saved to 1724719465100.json
