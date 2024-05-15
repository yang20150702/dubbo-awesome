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
# Warmup Iteration   1: 1.549 ops/ms
Iteration   1: 6.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.773 ops/ms


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
# Warmup Iteration   1: 7.003 ops/ms
Iteration   1: 11.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.403 ops/ms


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
# Warmup Iteration   1: 5.109 ops/ms
Iteration   1: 14.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.062 ops/ms


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
# Warmup Iteration   1: 4.721 ops/ms
Iteration   1: 8.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.292 ops/ms


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
# Warmup Iteration   1: 3.709 ±(99.9%) 0.070 ms/op
Iteration   1: 2.339 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.339 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.058 ms/op
Iteration   1: 1.761 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.761 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.053 ms/op
Iteration   1: 2.191 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.191 ms/op


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
# Warmup Iteration   1: 6.203 ±(99.9%) 0.163 ms/op
Iteration   1: 3.572 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.572 ms/op


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
# Warmup Iteration   1: 3.413 ±(99.9%) 0.087 ms/op
Iteration   1: 2.207 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   1.960 ms/op
                 createUser·p0.90:   2.599 ms/op
                 createUser·p0.95:   2.879 ms/op
                 createUser·p0.99:   12.857 ms/op
                 createUser·p0.999:  36.569 ms/op
                 createUser·p0.9999: 37.063 ms/op
                 createUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14614
  mean =      2.207 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12763 
    [ 2.500,  5.000) = 1633 
    [ 5.000,  7.500) = 25 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.599 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =     12.857 ms/op
     p(99.9000) =     36.569 ms/op
     p(99.9900) =     37.063 ms/op
     p(99.9990) =     37.093 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.083 ms/op
Iteration   1: 1.970 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   1.937 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  15.045 ms/op
                 existUser·p0.9999: 15.262 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16236
  mean =      1.970 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 813 
    [ 1.250,  2.500) = 14296 
    [ 2.500,  3.750) = 969 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =     15.045 ms/op
     p(99.9900) =     15.262 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.334 ±(99.9%) 0.103 ms/op
Iteration   1: 1.952 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   1.767 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  26.759 ms/op
                 getUser·p0.9999: 27.793 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16373
  mean =      1.952 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14954 
    [ 2.500,  5.000) = 1343 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     26.759 ms/op
     p(99.9900) =     27.793 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.192 ms/op
Iteration   1: 3.711 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.050 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 13.615 ms/op
                 listUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8630
  mean =      3.711 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 325 
    [ 2.500,  3.750) = 4234 
    [ 3.750,  5.000) = 3622 
    [ 5.000,  6.250) = 214 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.050 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.773          ops/ms
ClientSimple.existUser                       thrpt         11.403          ops/ms
ClientSimple.getUser                         thrpt         14.062          ops/ms
ClientSimple.listUser                        thrpt          8.292          ops/ms
ClientSimple.createUser                       avgt          2.339           ms/op
ClientSimple.existUser                        avgt          1.761           ms/op
ClientSimple.getUser                          avgt          2.191           ms/op
ClientSimple.listUser                         avgt          3.572           ms/op
ClientSimple.createUser                     sample  14614   2.207 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.692           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.960           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.599           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.857           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.569           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.063           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.093           ms/op
ClientSimple.existUser                      sample  16236   1.970 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.630           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.937           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.727           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.045           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.262           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.303           ms/op
ClientSimple.getUser                        sample  16373   1.952 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.686           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.767           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.415           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.759           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.793           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.148           ms/op
ClientSimple.listUser                       sample   8630   3.711 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.493           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.682           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.050           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.922           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.042           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.615           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.615           ms/op

Benchmark result is saved to 1715753528981.json
