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
# Warmup Iteration   1: 0.579 ops/ms
Iteration   1: 5.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.220 ops/ms


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
# Warmup Iteration   1: 5.773 ops/ms
Iteration   1: 13.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.044 ops/ms


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
# Warmup Iteration   1: 5.733 ops/ms
Iteration   1: 13.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.209 ops/ms


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
# Warmup Iteration   1: 5.541 ops/ms
Iteration   1: 8.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.929 ops/ms


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.069 ms/op
Iteration   1: 2.359 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.359 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.055 ms/op
Iteration   1: 1.865 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.865 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.100 ms/op
Iteration   1: 2.260 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.260 ms/op


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.096 ms/op
Iteration   1: 3.785 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.785 ms/op


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.126 ms/op
Iteration   1: 2.014 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   1.798 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   6.073 ms/op
                 createUser·p0.999:  13.404 ms/op
                 createUser·p0.9999: 13.734 ms/op
                 createUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15862
  mean =      2.014 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 14268 
    [ 2.500,  3.750) = 1086 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      6.073 ms/op
     p(99.9000) =     13.404 ms/op
     p(99.9900) =     13.734 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 3.238 ±(99.9%) 0.107 ms/op
Iteration   1: 1.831 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.363 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  18.711 ms/op
                 existUser·p0.9999: 18.792 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17608
  mean =      1.831 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 16799 
    [ 2.500,  3.750) = 459 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.363 ms/op
     p(99.0000) =      3.428 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     18.792 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.263 ±(99.9%) 0.078 ms/op
Iteration   1: 2.032 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   1.939 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   3.002 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  11.113 ms/op
                 getUser·p0.9999: 11.235 ms/op
                 getUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15742
  mean =      2.032 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 402 
    [ 1.250,  2.500) = 12608 
    [ 2.500,  3.750) = 2577 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =     11.113 ms/op
     p(99.9900) =     11.235 ms/op
     p(99.9990) =     11.272 ms/op
     p(99.9999) =     11.272 ms/op
    p(100.0000) =     11.272 ms/op


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
# Warmup Iteration   1: 5.057 ±(99.9%) 0.176 ms/op
Iteration   1: 3.592 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   5.980 ms/op
                 listUser·p0.999:  7.062 ms/op
                 listUser·p0.9999: 7.127 ms/op
                 listUser·p1.00:   7.127 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8907
  mean =      3.592 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 34 
    [1.500, 2.000) = 128 
    [2.000, 2.500) = 594 
    [2.500, 3.000) = 1048 
    [3.000, 3.500) = 2022 
    [3.500, 4.000) = 2893 
    [4.000, 4.500) = 1370 
    [4.500, 5.000) = 422 
    [5.000, 5.500) = 165 
    [5.500, 6.000) = 145 
    [6.000, 6.500) = 28 
    [6.500, 7.000) = 43 
    [7.000, 7.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =      7.127 ms/op
     p(99.9990) =      7.127 ms/op
     p(99.9999) =      7.127 ms/op
    p(100.0000) =      7.127 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.220          ops/ms
ClientSimple.existUser                       thrpt         13.044          ops/ms
ClientSimple.getUser                         thrpt         13.209          ops/ms
ClientSimple.listUser                        thrpt          8.929          ops/ms
ClientSimple.createUser                       avgt          2.359           ms/op
ClientSimple.existUser                        avgt          1.865           ms/op
ClientSimple.getUser                          avgt          2.260           ms/op
ClientSimple.listUser                         avgt          3.785           ms/op
ClientSimple.createUser                     sample  15862   2.014 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.686           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.798           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.073           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.404           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.734           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.926           ms/op
ClientSimple.existUser                      sample  17608   1.831 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.657           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.363           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.428           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.711           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.792           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.842           ms/op
ClientSimple.getUser                        sample  15742   2.032 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.654           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.939           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.002           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.703           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.113           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.235           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.272           ms/op
ClientSimple.listUser                       sample   8907   3.592 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.933           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.617           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.980           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.062           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.127           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.127           ms/op

Benchmark result is saved to 1721067169091.json
