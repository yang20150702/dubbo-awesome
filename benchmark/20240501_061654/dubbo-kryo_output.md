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
# Warmup Iteration   1: 1.200 ops/ms
Iteration   1: 6.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.801 ops/ms


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
# Warmup Iteration   1: 6.140 ops/ms
Iteration   1: 12.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.157 ops/ms


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
# Warmup Iteration   1: 5.846 ops/ms
Iteration   1: 13.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.302 ops/ms


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
# Warmup Iteration   1: 5.470 ops/ms
Iteration   1: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.205 ops/ms


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.065 ms/op
Iteration   1: 2.136 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.136 ms/op


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
# Warmup Iteration   1: 2.932 ±(99.9%) 0.062 ms/op
Iteration   1: 2.102 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.102 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 2.996 ±(99.9%) 0.054 ms/op
Iteration   1: 1.964 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.964 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.563 ±(99.9%) 0.089 ms/op
Iteration   1: 3.109 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.109 ms/op


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
# Warmup Iteration   1: 3.393 ±(99.9%) 0.099 ms/op
Iteration   1: 2.412 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   0.276 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   11.159 ms/op
                 createUser·p0.999:  49.676 ms/op
                 createUser·p0.9999: 52.101 ms/op
                 createUser·p1.00:   52.101 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13245
  mean =      2.412 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12989 
    [ 5.000, 10.000) = 96 
    [10.000, 15.000) = 120 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 25 
    [50.000, 55.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.276 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =     11.159 ms/op
     p(99.9000) =     49.676 ms/op
     p(99.9900) =     52.101 ms/op
     p(99.9990) =     52.101 ms/op
     p(99.9999) =     52.101 ms/op
    p(100.0000) =     52.101 ms/op


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
# Warmup Iteration   1: 2.869 ±(99.9%) 0.078 ms/op
Iteration   1: 2.104 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.013 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  22.407 ms/op
                 existUser·p0.9999: 22.772 ms/op
                 existUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15196
  mean =      2.104 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13377 
    [ 2.500,  5.000) = 1726 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =     22.407 ms/op
     p(99.9900) =     22.772 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.088 ms/op
Iteration   1: 2.208 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.826 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  17.400 ms/op
                 getUser·p0.9999: 18.160 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14596
  mean =      2.208 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 12239 
    [ 2.500,  3.750) = 2003 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     18.160 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.144 ms/op
Iteration   1: 3.393 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.330 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.467 ms/op
                 listUser·p0.999:  27.936 ms/op
                 listUser·p0.9999: 28.082 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9445
  mean =      3.393 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2108 
    [ 2.500,  5.000) = 7065 
    [ 5.000,  7.500) = 181 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.467 ms/op
     p(99.9000) =     27.936 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.801          ops/ms
ClientSimple.existUser                       thrpt         12.157          ops/ms
ClientSimple.getUser                         thrpt         13.302          ops/ms
ClientSimple.listUser                        thrpt          8.205          ops/ms
ClientSimple.createUser                       avgt          2.136           ms/op
ClientSimple.existUser                        avgt          2.102           ms/op
ClientSimple.getUser                          avgt          1.964           ms/op
ClientSimple.listUser                         avgt          3.109           ms/op
ClientSimple.createUser                     sample  13245   2.412 ± 0.075   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.276           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.159           ms/op
ClientSimple.createUser:createUser·p0.999   sample         49.676           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         52.101           ms/op
ClientSimple.createUser:createUser·p1.00    sample         52.101           ms/op
ClientSimple.existUser                      sample  15196   2.104 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.558           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.013           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.596           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.407           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.772           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.807           ms/op
ClientSimple.getUser                        sample  14596   2.208 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.908           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.546           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.400           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.160           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.612           ms/op
ClientSimple.listUser                       sample   9445   3.393 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.968           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.330           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.467           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.936           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.082           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.082           ms/op

Benchmark result is saved to 1714543963726.json
