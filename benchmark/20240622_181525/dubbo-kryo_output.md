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
# Warmup Iteration   1: 1.903 ops/ms
Iteration   1: 7.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.611 ops/ms


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
# Warmup Iteration   1: 5.974 ops/ms
Iteration   1: 11.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.404 ops/ms


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
# Warmup Iteration   1: 6.037 ops/ms
Iteration   1: 13.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.322 ops/ms


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
# Warmup Iteration   1: 6.321 ops/ms
Iteration   1: 9.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.194 ops/ms


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.076 ms/op
Iteration   1: 2.067 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.067 ms/op


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
# Warmup Iteration   1: 3.143 ±(99.9%) 0.050 ms/op
Iteration   1: 1.756 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.756 ms/op


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.066 ms/op
Iteration   1: 2.351 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.351 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ±(99.9%) 0.079 ms/op
Iteration   1: 3.339 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.339 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.714 ±(99.9%) 0.096 ms/op
Iteration   1: 2.408 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.353 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.920 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   11.881 ms/op
                 createUser·p0.999:  16.613 ms/op
                 createUser·p0.9999: 17.720 ms/op
                 createUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13285
  mean =      2.408 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 208 
    [ 1.250,  2.500) = 9942 
    [ 2.500,  3.750) = 2740 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.353 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =     11.881 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     17.720 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.521 ±(99.9%) 0.143 ms/op
Iteration   1: 2.010 ±(99.9%) 0.071 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   4.183 ms/op
                 existUser·p0.999:  57.278 ms/op
                 existUser·p0.9999: 60.385 ms/op
                 existUser·p1.00:   60.424 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15914
  mean =      2.010 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15757 
    [ 5.000, 10.000) = 59 
    [10.000, 15.000) = 31 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 27 
    [60.000, 65.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      4.183 ms/op
     p(99.9000) =     57.278 ms/op
     p(99.9900) =     60.385 ms/op
     p(99.9990) =     60.424 ms/op
     p(99.9999) =     60.424 ms/op
    p(100.0000) =     60.424 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.073 ms/op
Iteration   1: 2.433 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.900 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   4.746 ms/op
                 getUser·p0.999:  12.072 ms/op
                 getUser·p0.9999: 12.802 ms/op
                 getUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13159
  mean =      2.433 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 6829 
    [ 2.500,  3.750) = 5958 
    [ 3.750,  5.000) = 196 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      4.746 ms/op
     p(99.9000) =     12.072 ms/op
     p(99.9900) =     12.802 ms/op
     p(99.9990) =     12.812 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.174 ms/op
Iteration   1: 3.255 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.482 ms/op
                 listUser·p0.99:   6.119 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 14.467 ms/op
                 listUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9836
  mean =      3.255 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 772 
    [ 2.500,  3.750) = 6916 
    [ 3.750,  5.000) = 1827 
    [ 5.000,  6.250) = 239 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.482 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     12.583 ms/op
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
ClientSimple.createUser                      thrpt          7.611          ops/ms
ClientSimple.existUser                       thrpt         11.404          ops/ms
ClientSimple.getUser                         thrpt         13.322          ops/ms
ClientSimple.listUser                        thrpt          9.194          ops/ms
ClientSimple.createUser                       avgt          2.067           ms/op
ClientSimple.existUser                        avgt          1.756           ms/op
ClientSimple.getUser                          avgt          2.351           ms/op
ClientSimple.listUser                         avgt          3.339           ms/op
ClientSimple.createUser                     sample  13285   2.408 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.353           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.236           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.881           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.613           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.720           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.957           ms/op
ClientSimple.existUser                      sample  15914   2.010 ± 0.071   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.183           ms/op
ClientSimple.existUser:existUser·p0.999     sample         57.278           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         60.385           ms/op
ClientSimple.existUser:existUser·p1.00      sample         60.424           ms/op
ClientSimple.getUser                        sample  13159   2.433 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.683           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.060           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.746           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.072           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.802           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.812           ms/op
ClientSimple.listUser                       sample   9836   3.255 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.354           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.953           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.482           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.119           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.583           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.467           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.467           ms/op

Benchmark result is saved to 1719079879091.json
