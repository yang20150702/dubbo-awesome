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
# Warmup Iteration   1: 1.743 ops/ms
Iteration   1: 7.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.069 ops/ms


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
# Warmup Iteration   1: 5.962 ops/ms
Iteration   1: 13.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.153 ops/ms


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
# Warmup Iteration   1: 5.957 ops/ms
Iteration   1: 13.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.368 ops/ms


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
# Warmup Iteration   1: 6.304 ops/ms
Iteration   1: 8.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.764 ops/ms


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.084 ms/op
Iteration   1: 2.054 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.054 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.062 ms/op
Iteration   1: 1.822 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.822 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.086 ms/op
Iteration   1: 2.088 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.088 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.087 ms/op
Iteration   1: 3.525 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.525 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.089 ms/op
Iteration   1: 2.108 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   1.921 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.678 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 18.726 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15181
  mean =      2.108 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 13801 
    [ 2.500,  3.750) = 885 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.678 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     18.726 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.071 ms/op
Iteration   1: 2.093 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.241 ms/op
                 existUser·p0.50:   2.066 ms/op
                 existUser·p0.90:   2.556 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   4.185 ms/op
                 existUser·p0.999:  11.465 ms/op
                 existUser·p0.9999: 11.878 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15258
  mean =      2.093 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 451 
    [ 1.250,  2.500) = 12756 
    [ 2.500,  3.750) = 1841 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.241 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      4.185 ms/op
     p(99.9000) =     11.465 ms/op
     p(99.9900) =     11.878 ms/op
     p(99.9990) =     11.878 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


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
# Warmup Iteration   1: 3.313 ±(99.9%) 0.076 ms/op
Iteration   1: 2.089 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  11.474 ms/op
                 getUser·p0.9999: 12.237 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15701
  mean =      2.089 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 13773 
    [ 2.500,  3.750) = 1672 
    [ 3.750,  5.000) = 170 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =     11.474 ms/op
     p(99.9900) =     12.237 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.169 ms/op
Iteration   1: 3.490 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   5.840 ms/op
                 listUser·p0.999:  7.176 ms/op
                 listUser·p0.9999: 7.889 ms/op
                 listUser·p1.00:   7.889 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9214
  mean =      3.490 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 24 
    [1.500, 2.000) = 122 
    [2.000, 2.500) = 418 
    [2.500, 3.000) = 2271 
    [3.000, 3.500) = 2038 
    [3.500, 4.000) = 2107 
    [4.000, 4.500) = 1429 
    [4.500, 5.000) = 482 
    [5.000, 5.500) = 142 
    [5.500, 6.000) = 111 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 39 
    [7.000, 7.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      5.840 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =      7.889 ms/op
     p(99.9990) =      7.889 ms/op
     p(99.9999) =      7.889 ms/op
    p(100.0000) =      7.889 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.069          ops/ms
ClientSimple.existUser                       thrpt         13.153          ops/ms
ClientSimple.getUser                         thrpt         13.368          ops/ms
ClientSimple.listUser                        thrpt          8.764          ops/ms
ClientSimple.createUser                       avgt          2.054           ms/op
ClientSimple.existUser                        avgt          1.822           ms/op
ClientSimple.getUser                          avgt          2.088           ms/op
ClientSimple.listUser                         avgt          3.525           ms/op
ClientSimple.createUser                     sample  15181   2.108 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.450           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.921           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.678           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.971           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.350           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.726           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.743           ms/op
ClientSimple.existUser                      sample  15258   2.093 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.241           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.066           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.185           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.465           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.878           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.878           ms/op
ClientSimple.getUser                        sample  15701   2.089 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.705           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.047           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.924           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.474           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.237           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.648           ms/op
ClientSimple.listUser                       sample   9214   3.490 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.840           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.176           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.889           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.889           ms/op

Benchmark result is saved to 1724156303902.json
