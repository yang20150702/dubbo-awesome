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
# Warmup Iteration   1: 1.614 ops/ms
Iteration   1: 6.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.303 ops/ms


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
# Warmup Iteration   1: 5.863 ops/ms
Iteration   1: 10.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.901 ops/ms


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
# Warmup Iteration   1: 6.208 ops/ms
Iteration   1: 13.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.653 ops/ms


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
# Warmup Iteration   1: 5.159 ops/ms
Iteration   1: 9.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.328 ops/ms


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.064 ms/op
Iteration   1: 2.050 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.050 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.050 ms/op
Iteration   1: 1.912 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.912 ms/op


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
# Warmup Iteration   1: 3.326 ±(99.9%) 0.056 ms/op
Iteration   1: 1.995 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.995 ms/op


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.083 ms/op
Iteration   1: 3.603 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.603 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.084 ms/op
Iteration   1: 2.223 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   1.991 ms/op
                 createUser·p0.90:   2.728 ms/op
                 createUser·p0.95:   2.998 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  22.859 ms/op
                 createUser·p0.9999: 23.408 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14396
  mean =      2.223 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11961 
    [ 2.500,  5.000) = 2213 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     22.859 ms/op
     p(99.9900) =     23.408 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 2.883 ±(99.9%) 0.070 ms/op
Iteration   1: 1.681 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   1.593 ms/op
                 existUser·p0.90:   2.039 ms/op
                 existUser·p0.95:   2.228 ms/op
                 existUser·p0.99:   3.002 ms/op
                 existUser·p0.999:  14.533 ms/op
                 existUser·p0.9999: 15.244 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19001
  mean =      1.681 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 958 
    [ 1.250,  2.500) = 17634 
    [ 2.500,  3.750) = 320 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.593 ms/op
     p(90.0000) =      2.039 ms/op
     p(95.0000) =      2.228 ms/op
     p(99.0000) =      3.002 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     15.244 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.038 ±(99.9%) 0.082 ms/op
Iteration   1: 1.956 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.593 ms/op
                 getUser·p0.99:   3.844 ms/op
                 getUser·p0.999:  17.508 ms/op
                 getUser·p0.9999: 18.636 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16351
  mean =      1.956 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 344 
    [ 1.250,  2.500) = 14830 
    [ 2.500,  3.750) = 990 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.844 ms/op
     p(99.9000) =     17.508 ms/op
     p(99.9900) =     18.636 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.136 ms/op
Iteration   1: 3.210 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.960 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.964 ms/op
                 listUser·p0.999:  10.781 ms/op
                 listUser·p0.9999: 12.452 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10001
  mean =      3.210 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 746 
    [ 2.500,  3.750) = 7432 
    [ 3.750,  5.000) = 1648 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.960 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     10.781 ms/op
     p(99.9900) =     12.452 ms/op
     p(99.9990) =     12.452 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.303          ops/ms
ClientSimple.existUser                       thrpt         10.901          ops/ms
ClientSimple.getUser                         thrpt         13.653          ops/ms
ClientSimple.listUser                        thrpt          9.328          ops/ms
ClientSimple.createUser                       avgt          2.050           ms/op
ClientSimple.existUser                        avgt          1.912           ms/op
ClientSimple.getUser                          avgt          1.995           ms/op
ClientSimple.listUser                         avgt          3.603           ms/op
ClientSimple.createUser                     sample  14396   2.223 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.544           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.991           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.504           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.859           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.408           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.495           ms/op
ClientSimple.existUser                      sample  19001   1.681 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.665           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.593           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.039           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.002           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.533           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.244           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.303           ms/op
ClientSimple.getUser                        sample  16351   1.956 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.553           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.844           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.508           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.636           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.678           ms/op
ClientSimple.listUser                       sample  10001   3.210 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.243           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.019           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.960           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.964           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.781           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.452           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.452           ms/op

Benchmark result is saved to 1720851177541.json
