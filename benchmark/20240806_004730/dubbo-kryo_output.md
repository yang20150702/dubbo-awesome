# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.889 ops/ms
Iteration   1: 7.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.498 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.176 ops/ms
Iteration   1: 16.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  16.308 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.477 ops/ms
Iteration   1: 14.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.138 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.139 ops/ms
Iteration   1: 8.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.067 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.070 ms/op
Iteration   1: 2.130 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.342 ±(99.9%) 0.055 ms/op
Iteration   1: 2.029 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.029 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.053 ±(99.9%) 0.060 ms/op
Iteration   1: 2.001 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.544 ±(99.9%) 0.081 ms/op
Iteration   1: 3.897 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.086 ±(99.9%) 0.095 ms/op
Iteration   1: 2.294 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.349 ms/op
                 createUser·p0.50:   2.171 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   9.191 ms/op
                 createUser·p0.999:  14.860 ms/op
                 createUser·p0.9999: 15.595 ms/op
                 createUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13934
  mean =      2.294 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 10277 
    [ 2.500,  3.750) = 3210 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     15.595 ms/op
     p(99.9990) =     15.647 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.076 ±(99.9%) 0.069 ms/op
Iteration   1: 1.959 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   1.724 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   7.967 ms/op
                 existUser·p0.999:  27.252 ms/op
                 existUser·p0.9999: 28.377 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16485
  mean =      1.959 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15541 
    [ 2.500,  5.000) = 698 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      1.724 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      7.967 ms/op
     p(99.9000) =     27.252 ms/op
     p(99.9900) =     28.377 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.326 ±(99.9%) 0.073 ms/op
Iteration   1: 1.959 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   1.788 ms/op
                 getUser·p0.90:   2.298 ms/op
                 getUser·p0.95:   2.482 ms/op
                 getUser·p0.99:   4.398 ms/op
                 getUser·p0.999:  17.203 ms/op
                 getUser·p0.9999: 19.369 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16312
  mean =      1.959 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 15423 
    [ 2.500,  3.750) = 486 
    [ 3.750,  5.000) = 144 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      4.398 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     19.369 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.833 ±(99.9%) 0.193 ms/op
Iteration   1: 3.740 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  22.184 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8698
  mean =      3.740 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 692 
    [ 2.500,  5.000) = 7647 
    [ 5.000,  7.500) = 252 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.498          ops/ms
ClientSimple.existUser                       thrpt         16.308          ops/ms
ClientSimple.getUser                         thrpt         14.138          ops/ms
ClientSimple.listUser                        thrpt          8.067          ops/ms
ClientSimple.createUser                       avgt          2.130           ms/op
ClientSimple.existUser                        avgt          2.029           ms/op
ClientSimple.getUser                          avgt          2.001           ms/op
ClientSimple.listUser                         avgt          3.897           ms/op
ClientSimple.createUser                     sample  13934   2.294 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.349           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.171           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.068           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.191           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.860           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.595           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.647           ms/op
ClientSimple.existUser                      sample  16485   1.959 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.507           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.724           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          7.967           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.252           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.377           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.377           ms/op
ClientSimple.getUser                        sample  16312   1.959 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.788           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.398           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.203           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.369           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.431           ms/op
ClientSimple.listUser                       sample   8698   3.740 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.122           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.645           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.060           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.184           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.282           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.282           ms/op

Benchmark result is saved to 1722904975677.json
