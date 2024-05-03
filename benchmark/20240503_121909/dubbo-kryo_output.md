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
# Warmup Iteration   1: 1.511 ops/ms
Iteration   1: 6.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.812 ops/ms


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
# Warmup Iteration   1: 6.634 ops/ms
Iteration   1: 13.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.398 ops/ms


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
# Warmup Iteration   1: 5.446 ops/ms
Iteration   1: 12.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.302 ops/ms


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
# Warmup Iteration   1: 4.626 ops/ms
Iteration   1: 8.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.403 ops/ms


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.065 ms/op
Iteration   1: 2.164 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.164 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.055 ms/op
Iteration   1: 2.013 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.013 ms/op


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
# Warmup Iteration   1: 3.440 ±(99.9%) 0.065 ms/op
Iteration   1: 1.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.992 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.106 ms/op
Iteration   1: 3.001 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.001 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.081 ms/op
Iteration   1: 2.593 ±(99.9%) 0.072 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   2.310 ms/op
                 createUser·p0.90:   2.933 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  35.717 ms/op
                 createUser·p0.9999: 39.865 ms/op
                 createUser·p1.00:   40.108 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12320
  mean =      2.593 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12023 
    [ 5.000, 10.000) = 186 
    [10.000, 15.000) = 47 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 17 
    [30.000, 35.000) = 21 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     35.717 ms/op
     p(99.9900) =     39.865 ms/op
     p(99.9990) =     40.108 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


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
# Warmup Iteration   1: 3.038 ±(99.9%) 0.062 ms/op
Iteration   1: 2.055 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.703 ms/op
                 existUser·p0.95:   2.871 ms/op
                 existUser·p0.99:   3.978 ms/op
                 existUser·p0.999:  11.928 ms/op
                 existUser·p0.9999: 13.065 ms/op
                 existUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15557
  mean =      2.055 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 350 
    [ 1.250,  2.500) = 12095 
    [ 2.500,  3.750) = 2939 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      3.978 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     13.065 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


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
# Warmup Iteration   1: 3.181 ±(99.9%) 0.087 ms/op
Iteration   1: 2.180 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   2.101 ms/op
                 getUser·p0.90:   2.703 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   4.777 ms/op
                 getUser·p0.999:  18.254 ms/op
                 getUser·p0.9999: 19.121 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14783
  mean =      2.180 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 267 
    [ 1.250,  2.500) = 11935 
    [ 2.500,  3.750) = 2373 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      4.777 ms/op
     p(99.9000) =     18.254 ms/op
     p(99.9900) =     19.121 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 5.428 ±(99.9%) 0.199 ms/op
Iteration   1: 3.109 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.480 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.232 ms/op
                 listUser·p0.999:  12.202 ms/op
                 listUser·p0.9999: 12.845 ms/op
                 listUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10263
  mean =      3.109 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 2017 
    [ 2.500,  3.750) = 6604 
    [ 3.750,  5.000) = 1380 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.232 ms/op
     p(99.9000) =     12.202 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.812          ops/ms
ClientSimple.existUser                       thrpt         13.398          ops/ms
ClientSimple.getUser                         thrpt         12.302          ops/ms
ClientSimple.listUser                        thrpt          8.403          ops/ms
ClientSimple.createUser                       avgt          2.164           ms/op
ClientSimple.existUser                        avgt          2.013           ms/op
ClientSimple.getUser                          avgt          1.992           ms/op
ClientSimple.listUser                         avgt          3.001           ms/op
ClientSimple.createUser                     sample  12320   2.593 ± 0.072   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.549           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.310           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.252           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.781           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.717           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.865           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.108           ms/op
ClientSimple.existUser                      sample  15557   2.055 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.495           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.871           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.978           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.928           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.065           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.156           ms/op
ClientSimple.getUser                        sample  14783   2.180 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.504           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.101           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.777           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.254           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.121           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.137           ms/op
ClientSimple.listUser                       sample  10263   3.109 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.480           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.945           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.920           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.232           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.202           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.845           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.845           ms/op

Benchmark result is saved to 1714738479989.json
