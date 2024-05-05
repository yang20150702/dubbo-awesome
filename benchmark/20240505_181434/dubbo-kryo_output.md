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
# Warmup Iteration   1: 1.660 ops/ms
Iteration   1: 6.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.510 ops/ms


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
# Warmup Iteration   1: 6.779 ops/ms
Iteration   1: 14.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.677 ops/ms


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
# Warmup Iteration   1: 5.067 ops/ms
Iteration   1: 13.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.810 ops/ms


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
# Warmup Iteration   1: 4.341 ops/ms
Iteration   1: 8.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.223 ops/ms


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.084 ms/op
Iteration   1: 2.422 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.422 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.059 ms/op
Iteration   1: 1.966 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.966 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.056 ms/op
Iteration   1: 2.108 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.108 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.101 ms/op
Iteration   1: 3.348 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.348 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.140 ms/op
Iteration   1: 2.270 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   2.097 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  14.205 ms/op
                 createUser·p0.9999: 14.857 ms/op
                 createUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14065
  mean =      2.270 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 308 
    [ 1.250,  2.500) = 10219 
    [ 2.500,  3.750) = 3088 
    [ 3.750,  5.000) = 332 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     14.857 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.073 ms/op
Iteration   1: 1.753 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   1.554 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.140 ms/op
                 existUser·p0.999:  15.090 ms/op
                 existUser·p0.9999: 16.120 ms/op
                 existUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18232
  mean =      1.753 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2946 
    [ 1.250,  2.500) = 13869 
    [ 2.500,  3.750) = 1321 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.554 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.140 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     16.120 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.088 ms/op
Iteration   1: 1.937 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   1.737 ms/op
                 getUser·p0.90:   2.806 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  11.115 ms/op
                 getUser·p0.9999: 11.881 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16521
  mean =      1.937 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 14122 
    [ 2.500,  3.750) = 2168 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =     11.115 ms/op
     p(99.9900) =     11.881 ms/op
     p(99.9990) =     11.977 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.121 ms/op
Iteration   1: 3.444 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.237 ms/op
                 listUser·p0.999:  22.348 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9361
  mean =      3.444 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1119 
    [ 2.500,  5.000) = 7971 
    [ 5.000,  7.500) = 199 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.237 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.510          ops/ms
ClientSimple.existUser                       thrpt         14.677          ops/ms
ClientSimple.getUser                         thrpt         13.810          ops/ms
ClientSimple.listUser                        thrpt          8.223          ops/ms
ClientSimple.createUser                       avgt          2.422           ms/op
ClientSimple.existUser                        avgt          1.966           ms/op
ClientSimple.getUser                          avgt          2.108           ms/op
ClientSimple.listUser                         avgt          3.348           ms/op
ClientSimple.createUser                     sample  14065   2.270 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.447           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.097           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.338           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.584           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.743           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.205           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.857           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.877           ms/op
ClientSimple.existUser                      sample  18232   1.753 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.623           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.554           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.140           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.090           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.120           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.187           ms/op
ClientSimple.getUser                        sample  16521   1.937 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.727           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.737           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.633           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.115           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.881           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.977           ms/op
ClientSimple.listUser                       sample   9361   3.444 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.147           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.237           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.348           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.577           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.577           ms/op

Benchmark result is saved to 1714932625517.json
