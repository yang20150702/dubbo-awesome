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
# Warmup Iteration   1: 2.088 ops/ms
Iteration   1: 7.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.022 ops/ms


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
# Warmup Iteration   1: 6.440 ops/ms
Iteration   1: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.835 ops/ms


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
# Warmup Iteration   1: 5.132 ops/ms
Iteration   1: 13.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.146 ops/ms


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
# Warmup Iteration   1: 5.372 ops/ms
Iteration   1: 8.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.168 ops/ms


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.151 ms/op
Iteration   1: 2.522 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.522 ms/op


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
# Warmup Iteration   1: 3.102 ±(99.9%) 0.046 ms/op
Iteration   1: 1.874 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.874 ms/op


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.058 ms/op
Iteration   1: 2.290 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.290 ms/op


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.095 ms/op
Iteration   1: 3.140 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.140 ms/op


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.094 ms/op
Iteration   1: 2.293 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   5.354 ms/op
                 createUser·p0.999:  18.197 ms/op
                 createUser·p0.9999: 18.881 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13944
  mean =      2.293 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 10373 
    [ 2.500,  3.750) = 3120 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      5.354 ms/op
     p(99.9000) =     18.197 ms/op
     p(99.9900) =     18.881 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 2.813 ±(99.9%) 0.062 ms/op
Iteration   1: 1.932 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.383 ms/op
                 existUser·p0.99:   4.369 ms/op
                 existUser·p0.999:  29.458 ms/op
                 existUser·p0.9999: 32.303 ms/op
                 existUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16542
  mean =      1.932 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15951 
    [ 2.500,  5.000) = 442 
    [ 5.000,  7.500) = 53 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.383 ms/op
     p(99.0000) =      4.369 ms/op
     p(99.9000) =     29.458 ms/op
     p(99.9900) =     32.303 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.074 ms/op
Iteration   1: 2.136 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.487 ms/op
                 getUser·p0.50:   2.109 ms/op
                 getUser·p0.90:   2.703 ms/op
                 getUser·p0.95:   2.933 ms/op
                 getUser·p0.99:   3.664 ms/op
                 getUser·p0.999:  14.182 ms/op
                 getUser·p0.9999: 15.503 ms/op
                 getUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15141
  mean =      2.136 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 637 
    [ 1.250,  2.500) = 11424 
    [ 2.500,  3.750) = 2942 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      3.664 ms/op
     p(99.9000) =     14.182 ms/op
     p(99.9900) =     15.503 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.149 ms/op
Iteration   1: 3.283 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   2.968 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.215 ms/op
                 listUser·p0.999:  18.635 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9768
  mean =      3.283 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 534 
    [ 2.500,  3.750) = 7259 
    [ 3.750,  5.000) = 1635 
    [ 5.000,  6.250) = 196 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      2.968 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.215 ms/op
     p(99.9000) =     18.635 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.022          ops/ms
ClientSimple.existUser                       thrpt         12.835          ops/ms
ClientSimple.getUser                         thrpt         13.146          ops/ms
ClientSimple.listUser                        thrpt          8.168          ops/ms
ClientSimple.createUser                       avgt          2.522           ms/op
ClientSimple.existUser                        avgt          1.874           ms/op
ClientSimple.getUser                          avgt          2.290           ms/op
ClientSimple.listUser                         avgt          3.140           ms/op
ClientSimple.createUser                     sample  13944   2.293 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.605           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.354           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.197           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.881           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.907           ms/op
ClientSimple.existUser                      sample  16542   1.932 ± 0.044   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.830           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.383           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.369           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.458           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.303           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.539           ms/op
ClientSimple.getUser                        sample  15141   2.136 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.487           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.933           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.664           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.182           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.503           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.679           ms/op
ClientSimple.listUser                       sample   9768   3.283 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.225           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.968           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.080           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.215           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.635           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.759           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.759           ms/op

Benchmark result is saved to 1717807237851.json
