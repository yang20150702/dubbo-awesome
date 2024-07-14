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
# Warmup Iteration   1: 1.639 ops/ms
Iteration   1: 7.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.694 ops/ms


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
# Warmup Iteration   1: 5.353 ops/ms
Iteration   1: 10.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.521 ops/ms


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
# Warmup Iteration   1: 5.637 ops/ms
Iteration   1: 10.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.875 ops/ms


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
# Warmup Iteration   1: 4.241 ops/ms
Iteration   1: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.806 ops/ms


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.060 ms/op
Iteration   1: 2.091 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.091 ms/op


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.054 ms/op
Iteration   1: 2.403 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.403 ms/op


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
# Warmup Iteration   1: 3.180 ±(99.9%) 0.054 ms/op
Iteration   1: 1.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.987 ms/op


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
# Warmup Iteration   1: 4.512 ±(99.9%) 0.101 ms/op
Iteration   1: 3.067 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.067 ms/op


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.160 ms/op
Iteration   1: 2.270 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  17.760 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14081
  mean =      2.270 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 12013 
    [ 2.500,  3.750) = 1380 
    [ 3.750,  5.000) = 207 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.074 ms/op
Iteration   1: 2.002 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   1.868 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.834 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 15.224 ms/op
                 existUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15999
  mean =      2.002 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 273 
    [ 1.250,  2.500) = 13843 
    [ 2.500,  3.750) = 1735 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     15.224 ms/op
     p(99.9990) =     15.254 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.093 ms/op
Iteration   1: 2.067 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.338 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.703 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   3.187 ms/op
                 getUser·p0.999:  15.769 ms/op
                 getUser·p0.9999: 16.422 ms/op
                 getUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15502
  mean =      2.067 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 182 
    [ 1.250,  2.500) = 12530 
    [ 2.500,  3.750) = 2706 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.187 ms/op
     p(99.9000) =     15.769 ms/op
     p(99.9900) =     16.422 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.150 ms/op
Iteration   1: 3.316 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.501 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9650
  mean =      3.316 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 336 
    [ 2.500,  5.000) = 9109 
    [ 5.000,  7.500) = 163 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.501 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.694          ops/ms
ClientSimple.existUser                       thrpt         10.521          ops/ms
ClientSimple.getUser                         thrpt         10.875          ops/ms
ClientSimple.listUser                        thrpt          7.806          ops/ms
ClientSimple.createUser                       avgt          2.091           ms/op
ClientSimple.existUser                        avgt          2.403           ms/op
ClientSimple.getUser                          avgt          1.987           ms/op
ClientSimple.listUser                         avgt          3.067           ms/op
ClientSimple.createUser                     sample  14081   2.270 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.617           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.199           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.963           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.760           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.990           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.990           ms/op
ClientSimple.existUser                      sample  15999   2.002 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.615           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.868           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.834           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.490           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.813           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.224           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.254           ms/op
ClientSimple.getUser                        sample  15502   2.067 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.338           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.187           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.769           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.422           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.728           ms/op
ClientSimple.listUser                       sample   9650   3.316 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.430           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.039           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.501           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.201           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.234           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.234           ms/op

Benchmark result is saved to 1720981198905.json
