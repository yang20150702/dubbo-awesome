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
# Warmup Iteration   1: 1.876 ops/ms
Iteration   1: 8.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.098 ops/ms


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
# Warmup Iteration   1: 5.603 ops/ms
Iteration   1: 10.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.926 ops/ms


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
# Warmup Iteration   1: 5.871 ops/ms
Iteration   1: 14.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.522 ops/ms


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
# Warmup Iteration   1: 5.013 ops/ms
Iteration   1: 8.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.975 ops/ms


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
# Warmup Iteration   1: 3.511 ±(99.9%) 0.061 ms/op
Iteration   1: 2.097 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.097 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.052 ms/op
Iteration   1: 1.930 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.930 ms/op


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.055 ms/op
Iteration   1: 2.166 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.166 ms/op


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.083 ms/op
Iteration   1: 3.304 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.304 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.095 ms/op
Iteration   1: 2.272 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.464 ms/op
                 createUser·p0.50:   2.159 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 18.963 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14136
  mean =      2.272 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 282 
    [ 1.250,  2.500) = 10199 
    [ 2.500,  3.750) = 3393 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     18.963 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.094 ms/op
Iteration   1: 1.905 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  30.015 ms/op
                 existUser·p0.9999: 33.791 ms/op
                 existUser·p1.00:   40.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16782
  mean =      1.905 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16699 
    [ 5.000, 10.000) = 19 
    [10.000, 15.000) = 28 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 12 
    [30.000, 35.000) = 19 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.473 ms/op
     p(99.9000) =     30.015 ms/op
     p(99.9900) =     33.791 ms/op
     p(99.9990) =     40.370 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.166 ms/op
Iteration   1: 2.008 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.423 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  15.586 ms/op
                 getUser·p0.9999: 16.631 ms/op
                 getUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16145
  mean =      2.008 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 14050 
    [ 2.500,  3.750) = 1787 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =     15.586 ms/op
     p(99.9900) =     16.631 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.125 ms/op
Iteration   1: 3.553 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.525 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.695 ms/op
                 listUser·p0.99:   6.571 ms/op
                 listUser·p0.999:  22.872 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8996
  mean =      3.553 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1043 
    [ 2.500,  5.000) = 7697 
    [ 5.000,  7.500) = 207 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.525 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.695 ms/op
     p(99.0000) =      6.571 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.098          ops/ms
ClientSimple.existUser                       thrpt         10.926          ops/ms
ClientSimple.getUser                         thrpt         14.522          ops/ms
ClientSimple.listUser                        thrpt          8.975          ops/ms
ClientSimple.createUser                       avgt          2.097           ms/op
ClientSimple.existUser                        avgt          1.930           ms/op
ClientSimple.getUser                          avgt          2.166           ms/op
ClientSimple.listUser                         avgt          3.304           ms/op
ClientSimple.createUser                     sample  14136   2.272 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.464           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.159           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.907           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.481           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.963           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.071           ms/op
ClientSimple.existUser                      sample  16782   1.905 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.795           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.692           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.777           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.473           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.015           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.791           ms/op
ClientSimple.existUser:existUser·p1.00      sample         40.370           ms/op
ClientSimple.getUser                        sample  16145   2.008 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.423           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.584           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.586           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.631           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.712           ms/op
ClientSimple.listUser                       sample   8996   3.553 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.343           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.525           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.695           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.571           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.872           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.970           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.970           ms/op

Benchmark result is saved to 1720268102134.json
