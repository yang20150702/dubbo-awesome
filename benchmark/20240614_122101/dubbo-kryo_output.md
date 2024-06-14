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
# Warmup Iteration   1: 1.795 ops/ms
Iteration   1: 7.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.553 ops/ms


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
# Warmup Iteration   1: 5.026 ops/ms
Iteration   1: 12.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.414 ops/ms


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
# Warmup Iteration   1: 5.589 ops/ms
Iteration   1: 13.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.185 ops/ms


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
# Warmup Iteration   1: 5.167 ops/ms
Iteration   1: 8.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.879 ops/ms


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.084 ms/op
Iteration   1: 2.348 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.348 ms/op


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.068 ms/op
Iteration   1: 2.040 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.040 ms/op


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.059 ms/op
Iteration   1: 1.985 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.985 ms/op


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.104 ms/op
Iteration   1: 3.065 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.065 ms/op


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.097 ms/op
Iteration   1: 2.162 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   1.937 ms/op
                 createUser·p0.90:   2.269 ms/op
                 createUser·p0.95:   2.930 ms/op
                 createUser·p0.99:   10.175 ms/op
                 createUser·p0.999:  22.872 ms/op
                 createUser·p0.9999: 22.986 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15294
  mean =      2.162 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14198 
    [ 2.500,  5.000) = 747 
    [ 5.000,  7.500) = 84 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.930 ms/op
     p(99.0000) =     10.175 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     22.986 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 2.891 ±(99.9%) 0.062 ms/op
Iteration   1: 1.760 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   2.015 ms/op
                 existUser·p0.95:   2.232 ms/op
                 existUser·p0.99:   3.172 ms/op
                 existUser·p0.999:  30.436 ms/op
                 existUser·p0.9999: 31.139 ms/op
                 existUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18161
  mean =      1.760 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17730 
    [ 2.500,  5.000) = 353 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.015 ms/op
     p(95.0000) =      2.232 ms/op
     p(99.0000) =      3.172 ms/op
     p(99.9000) =     30.436 ms/op
     p(99.9900) =     31.139 ms/op
     p(99.9990) =     31.326 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.102 ms/op
Iteration   1: 1.967 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   1.866 ms/op
                 getUser·p0.90:   2.462 ms/op
                 getUser·p0.95:   2.826 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  12.569 ms/op
                 getUser·p0.9999: 15.316 ms/op
                 getUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16297
  mean =      1.967 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 491 
    [ 1.250,  2.500) = 14324 
    [ 2.500,  3.750) = 1309 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =     12.569 ms/op
     p(99.9900) =     15.316 ms/op
     p(99.9990) =     16.007 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.136 ms/op
Iteration   1: 3.482 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.728 ms/op
                 listUser·p0.50:   3.195 ms/op
                 listUser·p0.90:   4.627 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.239 ms/op
                 listUser·p0.999:  19.759 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9181
  mean =      3.482 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 958 
    [ 2.500,  5.000) = 7781 
    [ 5.000,  7.500) = 378 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.627 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.239 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.553          ops/ms
ClientSimple.existUser                       thrpt         12.414          ops/ms
ClientSimple.getUser                         thrpt         13.185          ops/ms
ClientSimple.listUser                        thrpt          8.879          ops/ms
ClientSimple.createUser                       avgt          2.348           ms/op
ClientSimple.existUser                        avgt          2.040           ms/op
ClientSimple.getUser                          avgt          1.985           ms/op
ClientSimple.listUser                         avgt          3.065           ms/op
ClientSimple.createUser                     sample  15294   2.162 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.531           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.937           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.930           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.175           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.872           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.986           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.003           ms/op
ClientSimple.existUser                      sample  18161   1.760 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.510           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.653           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.015           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.172           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.436           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.139           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.326           ms/op
ClientSimple.getUser                        sample  16297   1.967 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.647           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.866           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.846           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.569           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.316           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.007           ms/op
ClientSimple.listUser                       sample   9181   3.482 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.728           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.195           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.627           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.239           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.759           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.447           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.447           ms/op

Benchmark result is saved to 1718367396309.json
