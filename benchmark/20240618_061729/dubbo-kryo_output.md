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
# Warmup Iteration   1: 1.658 ops/ms
Iteration   1: 6.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.294 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.749 ops/ms
Iteration   1: 11.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.060 ops/ms


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
# Warmup Iteration   1: 7.304 ops/ms
Iteration   1: 14.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.046 ops/ms


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
# Warmup Iteration   1: 4.478 ops/ms
Iteration   1: 8.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.804 ops/ms


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.072 ms/op
Iteration   1: 1.959 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.959 ms/op


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.059 ms/op
Iteration   1: 1.851 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.851 ms/op


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
# Warmup Iteration   1: 3.044 ±(99.9%) 0.045 ms/op
Iteration   1: 1.879 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.879 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.092 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.091 ms/op


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.098 ms/op
Iteration   1: 2.228 ±(99.9%) 0.080 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   1.892 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   12.147 ms/op
                 createUser·p0.999:  55.551 ms/op
                 createUser·p0.9999: 56.238 ms/op
                 createUser·p1.00:   56.295 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14362
  mean =      2.228 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14138 
    [ 5.000, 10.000) = 26 
    [10.000, 15.000) = 85 
    [15.000, 20.000) = 77 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =     12.147 ms/op
     p(99.9000) =     55.551 ms/op
     p(99.9900) =     56.238 ms/op
     p(99.9990) =     56.295 ms/op
     p(99.9999) =     56.295 ms/op
    p(100.0000) =     56.295 ms/op


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
# Warmup Iteration   1: 3.065 ±(99.9%) 0.067 ms/op
Iteration   1: 1.777 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.390 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   1.991 ms/op
                 existUser·p0.95:   2.273 ms/op
                 existUser·p0.99:   2.839 ms/op
                 existUser·p0.999:  27.230 ms/op
                 existUser·p0.9999: 27.774 ms/op
                 existUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17995
  mean =      1.777 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17554 
    [ 2.500,  5.000) = 370 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      1.991 ms/op
     p(95.0000) =      2.273 ms/op
     p(99.0000) =      2.839 ms/op
     p(99.9000) =     27.230 ms/op
     p(99.9900) =     27.774 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 3.219 ±(99.9%) 0.082 ms/op
Iteration   1: 1.889 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.497 ms/op
                 getUser·p0.50:   1.780 ms/op
                 getUser·p0.90:   2.302 ms/op
                 getUser·p0.95:   2.511 ms/op
                 getUser·p0.99:   4.230 ms/op
                 getUser·p0.999:  13.468 ms/op
                 getUser·p0.9999: 13.865 ms/op
                 getUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16858
  mean =      1.889 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 436 
    [ 1.250,  2.500) = 15546 
    [ 2.500,  3.750) = 663 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      4.230 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     13.865 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.147 ms/op
Iteration   1: 3.270 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  22.086 ms/op
                 listUser·p0.9999: 22.217 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9771
  mean =      3.270 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 549 
    [ 2.500,  5.000) = 9036 
    [ 5.000,  7.500) = 88 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.294          ops/ms
ClientSimple.existUser                       thrpt         11.060          ops/ms
ClientSimple.getUser                         thrpt         14.046          ops/ms
ClientSimple.listUser                        thrpt          8.804          ops/ms
ClientSimple.createUser                       avgt          1.959           ms/op
ClientSimple.existUser                        avgt          1.851           ms/op
ClientSimple.getUser                          avgt          1.879           ms/op
ClientSimple.listUser                         avgt          3.091           ms/op
ClientSimple.createUser                     sample  14362   2.228 ± 0.080   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.653           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.892           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.147           ms/op
ClientSimple.createUser:createUser·p0.999   sample         55.551           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         56.238           ms/op
ClientSimple.createUser:createUser·p1.00    sample         56.295           ms/op
ClientSimple.existUser                      sample  17995   1.777 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.390           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.671           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.991           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.839           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.230           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.774           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.853           ms/op
ClientSimple.getUser                        sample  16858   1.889 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.497           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.780           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.302           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.230           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.468           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.865           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.910           ms/op
ClientSimple.listUser                       sample   9771   3.270 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.219           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.953           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.749           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.086           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.217           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.217           ms/op

Benchmark result is saved to 1718691192105.json
