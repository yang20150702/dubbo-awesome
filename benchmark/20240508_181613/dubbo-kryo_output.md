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
# Warmup Iteration   1: 1.938 ops/ms
Iteration   1: 6.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.089 ops/ms


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
# Warmup Iteration   1: 5.461 ops/ms
Iteration   1: 11.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.492 ops/ms


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
# Warmup Iteration   1: 5.958 ops/ms
Iteration   1: 13.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.758 ops/ms


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
# Warmup Iteration   1: 4.351 ops/ms
Iteration   1: 7.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.930 ops/ms


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.074 ms/op
Iteration   1: 2.222 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.222 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.077 ms/op
Iteration   1: 1.807 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.807 ms/op


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.066 ms/op
Iteration   1: 2.173 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.173 ms/op


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
# Warmup Iteration   1: 4.409 ±(99.9%) 0.093 ms/op
Iteration   1: 3.444 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.444 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.094 ms/op
Iteration   1: 2.381 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   2.249 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.115 ms/op
                 createUser·p0.99:   5.798 ms/op
                 createUser·p0.999:  21.823 ms/op
                 createUser·p0.9999: 22.592 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13423
  mean =      2.381 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9829 
    [ 2.500,  5.000) = 3378 
    [ 5.000,  7.500) = 119 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.115 ms/op
     p(99.0000) =      5.798 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     22.592 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 2.945 ±(99.9%) 0.068 ms/op
Iteration   1: 1.905 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.388 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.736 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  28.672 ms/op
                 existUser·p0.9999: 29.424 ms/op
                 existUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16860
  mean =      1.905 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15216 
    [ 2.500,  5.000) = 1550 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =     28.672 ms/op
     p(99.9900) =     29.424 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.080 ms/op
Iteration   1: 2.406 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   2.367 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.745 ms/op
                 getUser·p0.999:  12.698 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13386
  mean =      2.406 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 7728 
    [ 2.500,  3.750) = 5401 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.367 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.745 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.141 ms/op
Iteration   1: 3.680 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 13.746 ms/op
                 listUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8699
  mean =      3.680 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 432 
    [ 2.500,  3.750) = 4888 
    [ 3.750,  5.000) = 2966 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.089          ops/ms
ClientSimple.existUser                       thrpt         11.492          ops/ms
ClientSimple.getUser                         thrpt         13.758          ops/ms
ClientSimple.listUser                        thrpt          7.930          ops/ms
ClientSimple.createUser                       avgt          2.222           ms/op
ClientSimple.existUser                        avgt          1.807           ms/op
ClientSimple.getUser                          avgt          2.173           ms/op
ClientSimple.listUser                         avgt          3.444           ms/op
ClientSimple.createUser                     sample  13423   2.381 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.563           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.249           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.115           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.798           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.823           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.592           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.872           ms/op
ClientSimple.existUser                      sample  16860   1.905 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.388           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.736           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.822           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.672           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.424           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.491           ms/op
ClientSimple.getUser                        sample  13386   2.406 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.758           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.367           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.170           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.745           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.698           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.894           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.894           ms/op
ClientSimple.listUser                       sample   8699   3.680 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.585           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.537           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.681           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.746           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.746           ms/op

Benchmark result is saved to 1715191915692.json
