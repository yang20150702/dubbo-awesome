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
# Warmup Iteration   1: 1.680 ops/ms
Iteration   1: 6.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.918 ops/ms


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
# Warmup Iteration   1: 4.865 ops/ms
Iteration   1: 11.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.057 ops/ms


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
# Warmup Iteration   1: 5.635 ops/ms
Iteration   1: 12.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.202 ops/ms


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
# Warmup Iteration   1: 5.118 ops/ms
Iteration   1: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.082 ops/ms


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.091 ms/op
Iteration   1: 2.363 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.363 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.055 ms/op
Iteration   1: 1.831 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.831 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.071 ms/op
Iteration   1: 2.174 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.174 ms/op


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.095 ms/op
Iteration   1: 3.857 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.857 ms/op


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
# Warmup Iteration   1: 3.500 ±(99.9%) 0.090 ms/op
Iteration   1: 2.067 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   1.896 ms/op
                 createUser·p0.90:   2.392 ms/op
                 createUser·p0.95:   2.671 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  14.345 ms/op
                 createUser·p0.9999: 14.726 ms/op
                 createUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15459
  mean =      2.067 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 14241 
    [ 2.500,  3.750) = 979 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     14.345 ms/op
     p(99.9900) =     14.726 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.074 ms/op
Iteration   1: 1.872 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   3.680 ms/op
                 existUser·p0.999:  24.112 ms/op
                 existUser·p0.9999: 25.137 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17164
  mean =      1.872 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16032 
    [ 2.500,  5.000) = 1000 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.680 ms/op
     p(99.9000) =     24.112 ms/op
     p(99.9900) =     25.137 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.083 ms/op
Iteration   1: 2.138 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   2.077 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.847 ms/op
                 getUser·p0.99:   3.504 ms/op
                 getUser·p0.999:  11.827 ms/op
                 getUser·p0.9999: 14.440 ms/op
                 getUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15153
  mean =      2.138 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 12398 
    [ 2.500,  3.750) = 2429 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      3.504 ms/op
     p(99.9000) =     11.827 ms/op
     p(99.9900) =     14.440 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.156 ms/op
Iteration   1: 4.085 ±(99.9%) 0.075 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.745 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   16.089 ms/op
                 listUser·p0.999:  26.842 ms/op
                 listUser·p0.9999: 27.591 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7837
  mean =      4.085 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 331 
    [ 2.500,  5.000) = 6975 
    [ 5.000,  7.500) = 418 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.745 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =     16.089 ms/op
     p(99.9000) =     26.842 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.918          ops/ms
ClientSimple.existUser                       thrpt         11.057          ops/ms
ClientSimple.getUser                         thrpt         12.202          ops/ms
ClientSimple.listUser                        thrpt          9.082          ops/ms
ClientSimple.createUser                       avgt          2.363           ms/op
ClientSimple.existUser                        avgt          1.831           ms/op
ClientSimple.getUser                          avgt          2.174           ms/op
ClientSimple.listUser                         avgt          3.857           ms/op
ClientSimple.createUser                     sample  15459   2.067 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.094           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.896           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.392           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.423           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.345           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.726           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.762           ms/op
ClientSimple.existUser                      sample  17164   1.872 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.450           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.661           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.680           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.112           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.137           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.231           ms/op
ClientSimple.getUser                        sample  15153   2.138 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.575           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.077           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.504           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.827           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.440           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.533           ms/op
ClientSimple.listUser                       sample   7837   4.085 ± 0.075   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.190           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.928           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.745           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.210           ms/op
ClientSimple.listUser:listUser·p0.99        sample         16.089           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.842           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.591           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.591           ms/op

Benchmark result is saved to 1717524742147.json
