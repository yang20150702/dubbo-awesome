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
# Warmup Iteration   1: 1.689 ops/ms
Iteration   1: 6.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.790 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 6.089 ops/ms
Iteration   1: 12.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.167 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.449 ops/ms
Iteration   1: 13.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.963 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ops/ms
Iteration   1: 9.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.092 ops/ms


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
# Warmup Iteration   1: 4.982 ±(99.9%) 0.134 ms/op
Iteration   1: 2.272 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.272 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.067 ms/op
Iteration   1: 1.734 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.734 ms/op


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.064 ms/op
Iteration   1: 2.196 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.196 ms/op


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.077 ms/op
Iteration   1: 3.315 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.315 ms/op


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
# Warmup Iteration   1: 3.608 ±(99.9%) 0.095 ms/op
Iteration   1: 2.156 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   1.958 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  15.254 ms/op
                 createUser·p0.9999: 16.073 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14891
  mean =      2.156 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 12500 
    [ 2.500,  3.750) = 1955 
    [ 3.750,  5.000) = 149 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     16.073 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 2.907 ±(99.9%) 0.060 ms/op
Iteration   1: 1.755 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   1.618 ms/op
                 existUser·p0.90:   2.114 ms/op
                 existUser·p0.95:   2.331 ms/op
                 existUser·p0.99:   2.940 ms/op
                 existUser·p0.999:  21.620 ms/op
                 existUser·p0.9999: 21.862 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18220
  mean =      1.755 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17671 
    [ 2.500,  5.000) = 438 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      2.114 ms/op
     p(95.0000) =      2.331 ms/op
     p(99.0000) =      2.940 ms/op
     p(99.9000) =     21.620 ms/op
     p(99.9900) =     21.862 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.335 ±(99.9%) 0.081 ms/op
Iteration   1: 2.021 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   1.943 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.761 ms/op
                 getUser·p0.99:   3.156 ms/op
                 getUser·p0.999:  13.110 ms/op
                 getUser·p0.9999: 13.987 ms/op
                 getUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15852
  mean =      2.021 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 14133 
    [ 2.500,  3.750) = 1589 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      1.943 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      3.156 ms/op
     p(99.9000) =     13.110 ms/op
     p(99.9900) =     13.987 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.138 ms/op
Iteration   1: 3.551 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  7.028 ms/op
                 listUser·p0.9999: 8.176 ms/op
                 listUser·p1.00:   8.176 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9015
  mean =      3.551 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 1 
    [1.500, 2.000) = 39 
    [2.000, 2.500) = 513 
    [2.500, 3.000) = 1293 
    [3.000, 3.500) = 2247 
    [3.500, 4.000) = 2767 
    [4.000, 4.500) = 1611 
    [4.500, 5.000) = 377 
    [5.000, 5.500) = 104 
    [5.500, 6.000) = 34 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      7.028 ms/op
     p(99.9900) =      8.176 ms/op
     p(99.9990) =      8.176 ms/op
     p(99.9999) =      8.176 ms/op
    p(100.0000) =      8.176 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.790          ops/ms
ClientSimple.existUser                       thrpt         12.167          ops/ms
ClientSimple.getUser                         thrpt         13.963          ops/ms
ClientSimple.listUser                        thrpt          9.092          ops/ms
ClientSimple.createUser                       avgt          2.272           ms/op
ClientSimple.existUser                        avgt          1.734           ms/op
ClientSimple.getUser                          avgt          2.196           ms/op
ClientSimple.listUser                         avgt          3.315           ms/op
ClientSimple.createUser                     sample  14891   2.156 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.742           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.958           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.399           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.254           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.073           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.073           ms/op
ClientSimple.existUser                      sample  18220   1.755 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.537           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.618           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.114           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.940           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.620           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.862           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.889           ms/op
ClientSimple.getUser                        sample  15852   2.021 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.650           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.943           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.156           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.110           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.987           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.189           ms/op
ClientSimple.listUser                       sample   9015   3.551 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.245           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.415           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.028           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.176           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.176           ms/op

Benchmark result is saved to 1714759874492.json
