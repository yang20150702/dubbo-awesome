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
# Warmup Iteration   1: 1.549 ops/ms
Iteration   1: 6.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.829 ops/ms


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
# Warmup Iteration   1: 6.303 ops/ms
Iteration   1: 11.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.549 ops/ms


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
# Warmup Iteration   1: 4.852 ops/ms
Iteration   1: 10.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.889 ops/ms


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
# Warmup Iteration   1: 5.129 ops/ms
Iteration   1: 8.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.938 ops/ms


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.086 ms/op
Iteration   1: 2.005 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.005 ms/op


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
# Warmup Iteration   1: 2.969 ±(99.9%) 0.045 ms/op
Iteration   1: 1.782 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.782 ms/op


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.077 ms/op
Iteration   1: 2.380 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.380 ms/op


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.084 ms/op
Iteration   1: 3.990 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.990 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.096 ms/op
Iteration   1: 2.145 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   1.866 ms/op
                 createUser·p0.90:   2.486 ms/op
                 createUser·p0.95:   2.728 ms/op
                 createUser·p0.99:   9.340 ms/op
                 createUser·p0.999:  37.224 ms/op
                 createUser·p0.9999: 38.240 ms/op
                 createUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14994
  mean =      2.145 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13592 
    [ 2.500,  5.000) = 1071 
    [ 5.000,  7.500) = 134 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      9.340 ms/op
     p(99.9000) =     37.224 ms/op
     p(99.9900) =     38.240 ms/op
     p(99.9990) =     38.273 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 2.993 ±(99.9%) 0.066 ms/op
Iteration   1: 1.900 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  18.264 ms/op
                 existUser·p0.9999: 18.991 ms/op
                 existUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16902
  mean =      1.900 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 15658 
    [ 2.500,  3.750) = 942 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =     18.264 ms/op
     p(99.9900) =     18.991 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.100 ms/op
Iteration   1: 2.317 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.191 ms/op
                 getUser·p0.90:   2.777 ms/op
                 getUser·p0.95:   3.145 ms/op
                 getUser·p0.99:   5.922 ms/op
                 getUser·p0.999:  11.290 ms/op
                 getUser·p0.9999: 11.502 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13901
  mean =      2.317 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 10486 
    [ 2.500,  3.750) = 2923 
    [ 3.750,  5.000) = 191 
    [ 5.000,  6.250) = 107 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      3.145 ms/op
     p(99.0000) =      5.922 ms/op
     p(99.9000) =     11.290 ms/op
     p(99.9900) =     11.502 ms/op
     p(99.9990) =     11.502 ms/op
     p(99.9999) =     11.502 ms/op
    p(100.0000) =     11.502 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.133 ms/op
Iteration   1: 3.433 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   3.334 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.763 ms/op
                 listUser·p0.99:   6.150 ms/op
                 listUser·p0.999:  14.347 ms/op
                 listUser·p0.9999: 16.138 ms/op
                 listUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9330
  mean =      3.433 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 723 
    [ 2.500,  3.750) = 5956 
    [ 3.750,  5.000) = 2263 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.763 ms/op
     p(99.0000) =      6.150 ms/op
     p(99.9000) =     14.347 ms/op
     p(99.9900) =     16.138 ms/op
     p(99.9990) =     16.138 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.829          ops/ms
ClientSimple.existUser                       thrpt         11.549          ops/ms
ClientSimple.getUser                         thrpt         10.889          ops/ms
ClientSimple.listUser                        thrpt          8.938          ops/ms
ClientSimple.createUser                       avgt          2.005           ms/op
ClientSimple.existUser                        avgt          1.782           ms/op
ClientSimple.getUser                          avgt          2.380           ms/op
ClientSimple.listUser                         avgt          3.990           ms/op
ClientSimple.createUser                     sample  14994   2.145 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.651           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.866           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.340           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.224           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.240           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.273           ms/op
ClientSimple.existUser                      sample  16902   1.900 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.762           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.625           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.264           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.991           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.104           ms/op
ClientSimple.getUser                        sample  13901   2.317 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.742           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.191           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.145           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.922           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.290           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.502           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.502           ms/op
ClientSimple.listUser                       sample   9330   3.433 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.813           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.334           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.763           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.150           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.347           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.138           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.138           ms/op

Benchmark result is saved to 1716984972475.json
