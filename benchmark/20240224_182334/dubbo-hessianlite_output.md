# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.297 ops/ms
Iteration   1: 5.802 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.802 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.625 ops/ms
Iteration   1: 13.825 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.825 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.374 ops/ms
Iteration   1: 7.521 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.521 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.060 ops/ms
Iteration   1: 3.808 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.808 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.452 ±(99.9%) 0.101 ms/op
Iteration   1: 3.260 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.260 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ±(99.9%) 0.033 ms/op
Iteration   1: 1.781 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.781 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.934 ±(99.9%) 0.060 ms/op
Iteration   1: 2.903 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.732 ±(99.9%) 0.195 ms/op
Iteration   1: 8.662 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.662 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.275 ±(99.9%) 0.159 ms/op
Iteration   1: 3.325 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   8.318 ms/op
                 createUser·p0.999:  10.818 ms/op
                 createUser·p0.9999: 13.287 ms/op
                 createUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9733
  mean =      3.325 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1379 
    [ 2.500,  3.750) = 6300 
    [ 3.750,  5.000) = 1488 
    [ 5.000,  6.250) = 168 
    [ 6.250,  7.500) = 238 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.318 ms/op
     p(99.9000) =     10.818 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.878 ±(99.9%) 0.086 ms/op
Iteration   1: 1.751 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.368 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  6.578 ms/op
                 existUser·p0.9999: 10.008 ms/op
                 existUser·p1.00:   10.076 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18270
  mean =      1.751 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 391 
    [ 1.000,  2.000) = 14941 
    [ 2.000,  3.000) = 2589 
    [ 3.000,  4.000) = 224 
    [ 4.000,  5.000) = 43 
    [ 5.000,  6.000) = 11 
    [ 6.000,  7.000) = 64 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     10.008 ms/op
     p(99.9990) =     10.076 ms/op
     p(99.9999) =     10.076 ms/op
    p(100.0000) =     10.076 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ±(99.9%) 0.117 ms/op
Iteration   1: 3.186 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  8.150 ms/op
                 getUser·p0.9999: 9.469 ms/op
                 getUser·p1.00:   9.470 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10048
  mean =      3.186 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 3 
    [ 1.000,  2.000) = 158 
    [ 2.000,  3.000) = 3779 
    [ 3.000,  4.000) = 5359 
    [ 4.000,  5.000) = 613 
    [ 5.000,  6.000) = 99 
    [ 6.000,  7.000) = 19 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      8.150 ms/op
     p(99.9900) =      9.469 ms/op
     p(99.9990) =      9.470 ms/op
     p(99.9999) =      9.470 ms/op
    p(100.0000) =      9.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.136 ±(99.9%) 0.435 ms/op
Iteration   1: 8.188 ±(99.9%) 0.149 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   7.733 ms/op
                 listUser·p0.90:   10.469 ms/op
                 listUser·p0.95:   11.765 ms/op
                 listUser·p0.99:   20.614 ms/op
                 listUser·p0.999:  34.045 ms/op
                 listUser·p0.9999: 36.438 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3945
  mean =      8.188 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 107 
    [ 5.000,  7.500) = 1632 
    [ 7.500, 10.000) = 1696 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      7.733 ms/op
     p(90.0000) =     10.469 ms/op
     p(95.0000) =     11.765 ms/op
     p(99.0000) =     20.614 ms/op
     p(99.9000) =     34.045 ms/op
     p(99.9900) =     36.438 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.802          ops/ms
Client.existUser                       thrpt         13.825          ops/ms
Client.getUser                         thrpt          7.521          ops/ms
Client.listUser                        thrpt          3.808          ops/ms
Client.createUser                       avgt          3.260           ms/op
Client.existUser                        avgt          1.781           ms/op
Client.getUser                          avgt          2.903           ms/op
Client.listUser                         avgt          8.662           ms/op
Client.createUser                     sample   9733   3.325 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.165           ms/op
Client.createUser:createUser·p0.50    sample          2.994           ms/op
Client.createUser:createUser·p0.90    sample          4.424           ms/op
Client.createUser:createUser·p0.95    sample          5.341           ms/op
Client.createUser:createUser·p0.99    sample          8.318           ms/op
Client.createUser:createUser·p0.999   sample         10.818           ms/op
Client.createUser:createUser·p0.9999  sample         13.287           ms/op
Client.createUser:createUser·p1.00    sample         13.287           ms/op
Client.existUser                      sample  18270   1.751 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.368           ms/op
Client.existUser:existUser·p0.50      sample          1.673           ms/op
Client.existUser:existUser·p0.90      sample          2.122           ms/op
Client.existUser:existUser·p0.95      sample          2.433           ms/op
Client.existUser:existUser·p0.99      sample          3.740           ms/op
Client.existUser:existUser·p0.999     sample          6.578           ms/op
Client.existUser:existUser·p0.9999    sample         10.008           ms/op
Client.existUser:existUser·p1.00      sample         10.076           ms/op
Client.getUser                        sample  10048   3.186 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.974           ms/op
Client.getUser:getUser·p0.50          sample          3.162           ms/op
Client.getUser:getUser·p0.90          sample          3.895           ms/op
Client.getUser:getUser·p0.95          sample          4.235           ms/op
Client.getUser:getUser·p0.99          sample          5.202           ms/op
Client.getUser:getUser·p0.999         sample          8.150           ms/op
Client.getUser:getUser·p0.9999        sample          9.469           ms/op
Client.getUser:getUser·p1.00          sample          9.470           ms/op
Client.listUser                       sample   3945   8.188 ± 0.149   ms/op
Client.listUser:listUser·p0.00        sample          1.661           ms/op
Client.listUser:listUser·p0.50        sample          7.733           ms/op
Client.listUser:listUser·p0.90        sample         10.469           ms/op
Client.listUser:listUser·p0.95        sample         11.765           ms/op
Client.listUser:listUser·p0.99        sample         20.614           ms/op
Client.listUser:listUser·p0.999       sample         34.045           ms/op
Client.listUser:listUser·p0.9999      sample         36.438           ms/op
Client.listUser:listUser·p1.00        sample         36.438           ms/op
