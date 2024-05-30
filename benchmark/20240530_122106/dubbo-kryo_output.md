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
# Warmup Iteration   1: 1.405 ops/ms
Iteration   1: 6.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.059 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ops/ms
Iteration   1: 10.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.858 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.199 ops/ms
Iteration   1: 11.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.681 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ops/ms
Iteration   1: 7.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.545 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.156 ±(99.9%) 0.117 ms/op
Iteration   1: 2.658 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.658 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ±(99.9%) 0.051 ms/op
Iteration   1: 2.054 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.054 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ±(99.9%) 0.084 ms/op
Iteration   1: 2.165 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.165 ms/op


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
# Warmup Iteration   1: 5.860 ±(99.9%) 0.135 ms/op
Iteration   1: 3.861 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.861 ms/op


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.117 ms/op
Iteration   1: 2.185 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.507 ms/op
                 createUser·p0.50:   1.937 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.997 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  20.231 ms/op
                 createUser·p0.9999: 21.171 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14606
  mean =      2.185 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12616 
    [ 2.500,  5.000) = 1627 
    [ 5.000,  7.500) = 201 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.997 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     20.231 ms/op
     p(99.9900) =     21.171 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.096 ms/op
Iteration   1: 2.109 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   1.946 ms/op
                 existUser·p0.90:   2.634 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  10.994 ms/op
                 existUser·p0.9999: 12.287 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15214
  mean =      2.109 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 167 
    [ 1.250,  2.500) = 12673 
    [ 2.500,  3.750) = 2205 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     10.994 ms/op
     p(99.9900) =     12.287 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 3.615 ±(99.9%) 0.099 ms/op
Iteration   1: 1.788 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   1.608 ms/op
                 getUser·p0.90:   2.187 ms/op
                 getUser·p0.95:   2.548 ms/op
                 getUser·p0.99:   4.761 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 19.125 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17868
  mean =      1.788 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 256 
    [ 1.250,  2.500) = 16674 
    [ 2.500,  3.750) = 717 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.608 ms/op
     p(90.0000) =      2.187 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      4.761 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.125 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.896 ±(99.9%) 0.152 ms/op
Iteration   1: 3.351 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.841 ms/op
                 listUser·p0.999:  15.383 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9538
  mean =      3.351 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 282 
    [ 2.500,  3.750) = 6678 
    [ 3.750,  5.000) = 2338 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     15.383 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.059          ops/ms
ClientSimple.existUser                       thrpt         10.858          ops/ms
ClientSimple.getUser                         thrpt         11.681          ops/ms
ClientSimple.listUser                        thrpt          7.545          ops/ms
ClientSimple.createUser                       avgt          2.658           ms/op
ClientSimple.existUser                        avgt          2.054           ms/op
ClientSimple.getUser                          avgt          2.165           ms/op
ClientSimple.listUser                         avgt          3.861           ms/op
ClientSimple.createUser                     sample  14606   2.185 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.507           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.937           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.997           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.995           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.231           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.171           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.201           ms/op
ClientSimple.existUser                      sample  15214   2.109 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.647           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.946           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.522           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.994           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.287           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.517           ms/op
ClientSimple.getUser                        sample  17868   1.788 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.418           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.608           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.187           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.761           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.940           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.125           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.202           ms/op
ClientSimple.listUser                       sample   9538   3.351 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.169           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.088           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.841           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.383           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.958           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.958           ms/op

Benchmark result is saved to 1717071388374.json
