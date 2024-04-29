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
# Warmup Iteration   1: 1.498 ops/ms
Iteration   1: 7.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.473 ops/ms


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
# Warmup Iteration   1: 5.097 ops/ms
Iteration   1: 11.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.555 ops/ms


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
# Warmup Iteration   1: 5.286 ops/ms
Iteration   1: 13.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.971 ops/ms


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
# Warmup Iteration   1: 5.057 ops/ms
Iteration   1: 7.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.376 ops/ms


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.070 ms/op
Iteration   1: 1.976 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.976 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.067 ms/op
Iteration   1: 1.782 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.782 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.069 ms/op
Iteration   1: 1.846 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.846 ms/op


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.098 ms/op
Iteration   1: 3.484 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.484 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.108 ms/op
Iteration   1: 1.936 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   1.788 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  14.942 ms/op
                 createUser·p0.9999: 16.270 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16498
  mean =      1.936 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1512 
    [ 1.250,  2.500) = 13072 
    [ 2.500,  3.750) = 1666 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     16.270 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.087 ms/op
Iteration   1: 2.271 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   2.230 ms/op
                 existUser·p0.90:   2.814 ms/op
                 existUser·p0.95:   3.048 ms/op
                 existUser·p0.99:   4.007 ms/op
                 existUser·p0.999:  14.940 ms/op
                 existUser·p0.9999: 15.696 ms/op
                 existUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14076
  mean =      2.271 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 328 
    [ 1.250,  2.500) = 9527 
    [ 2.500,  3.750) = 3995 
    [ 3.750,  5.000) = 185 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      2.230 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.048 ms/op
     p(99.0000) =      4.007 ms/op
     p(99.9000) =     14.940 ms/op
     p(99.9900) =     15.696 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.089 ms/op
Iteration   1: 1.940 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.314 ms/op
                 getUser·p0.95:   2.507 ms/op
                 getUser·p0.99:   3.253 ms/op
                 getUser·p0.999:  12.034 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16527
  mean =      1.940 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 15630 
    [ 2.500,  3.750) = 726 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.253 ms/op
     p(99.9000) =     12.034 ms/op
     p(99.9900) =     12.190 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


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
# Warmup Iteration   1: 5.538 ±(99.9%) 0.173 ms/op
Iteration   1: 3.668 ±(99.9%) 0.108 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.556 ms/op
                 listUser·p0.999:  55.902 ms/op
                 listUser·p0.9999: 57.737 ms/op
                 listUser·p1.00:   57.737 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8718
  mean =      3.668 ±(99.9%) 0.108 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8432 
    [ 5.000, 10.000) = 210 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.556 ms/op
     p(99.9000) =     55.902 ms/op
     p(99.9900) =     57.737 ms/op
     p(99.9990) =     57.737 ms/op
     p(99.9999) =     57.737 ms/op
    p(100.0000) =     57.737 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.473          ops/ms
ClientSimple.existUser                       thrpt         11.555          ops/ms
ClientSimple.getUser                         thrpt         13.971          ops/ms
ClientSimple.listUser                        thrpt          7.376          ops/ms
ClientSimple.createUser                       avgt          1.976           ms/op
ClientSimple.existUser                        avgt          1.782           ms/op
ClientSimple.getUser                          avgt          1.846           ms/op
ClientSimple.listUser                         avgt          3.484           ms/op
ClientSimple.createUser                     sample  16498   1.936 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.667           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.788           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.014           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.942           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.270           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.302           ms/op
ClientSimple.existUser                      sample  14076   2.271 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.492           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.230           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.814           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.048           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.007           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.940           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.696           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.876           ms/op
ClientSimple.getUser                        sample  16527   1.940 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.912           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.314           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.253           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.034           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.190           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.190           ms/op
ClientSimple.listUser                       sample   8718   3.668 ± 0.108   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.949           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.556           ms/op
ClientSimple.listUser:listUser·p0.999       sample         55.902           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         57.737           ms/op
ClientSimple.listUser:listUser·p1.00        sample         57.737           ms/op

Benchmark result is saved to 1714351131735.json
