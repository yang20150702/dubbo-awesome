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
# Warmup Iteration   1: 1.907 ops/ms
Iteration   1: 7.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.025 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.176 ops/ms
Iteration   1: 11.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.848 ops/ms


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
# Warmup Iteration   1: 6.143 ops/ms
Iteration   1: 13.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.284 ops/ms


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
# Warmup Iteration   1: 5.879 ops/ms
Iteration   1: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.288 ops/ms


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
# Warmup Iteration   1: 4.686 ±(99.9%) 0.132 ms/op
Iteration   1: 2.104 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.104 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.051 ms/op
Iteration   1: 1.999 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.999 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.087 ms/op
Iteration   1: 2.152 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.152 ms/op


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.100 ms/op
Iteration   1: 3.279 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.279 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.101 ms/op
Iteration   1: 2.096 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.429 ms/op
                 createUser·p0.95:   2.699 ms/op
                 createUser·p0.99:   4.908 ms/op
                 createUser·p0.999:  20.611 ms/op
                 createUser·p0.9999: 25.289 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15592
  mean =      2.096 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14352 
    [ 2.500,  5.000) = 1097 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      4.908 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     25.289 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.113 ms/op
Iteration   1: 1.863 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   3.047 ms/op
                 existUser·p0.999:  11.969 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17454
  mean =      1.863 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 16027 
    [ 2.500,  3.750) = 1000 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.047 ms/op
     p(99.9000) =     11.969 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     12.550 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


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
# Warmup Iteration   1: 3.291 ±(99.9%) 0.087 ms/op
Iteration   1: 2.141 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.404 ms/op
                 getUser·p0.50:   2.007 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.888 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  22.867 ms/op
                 getUser·p0.9999: 23.772 ms/op
                 getUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15164
  mean =      2.141 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12908 
    [ 2.500,  5.000) = 2158 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     22.867 ms/op
     p(99.9900) =     23.772 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 5.755 ±(99.9%) 0.156 ms/op
Iteration   1: 3.550 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   6.600 ms/op
                 listUser·p0.999:  15.007 ms/op
                 listUser·p0.9999: 16.122 ms/op
                 listUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9033
  mean =      3.550 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 776 
    [ 2.500,  3.750) = 4556 
    [ 3.750,  5.000) = 3262 
    [ 5.000,  6.250) = 319 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.600 ms/op
     p(99.9000) =     15.007 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     16.122 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.025          ops/ms
ClientSimple.existUser                       thrpt         11.848          ops/ms
ClientSimple.getUser                         thrpt         13.284          ops/ms
ClientSimple.listUser                        thrpt          8.288          ops/ms
ClientSimple.createUser                       avgt          2.104           ms/op
ClientSimple.existUser                        avgt          1.999           ms/op
ClientSimple.getUser                          avgt          2.152           ms/op
ClientSimple.listUser                         avgt          3.279           ms/op
ClientSimple.createUser                     sample  15592   2.096 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.822           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.429           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.908           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.611           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.289           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.362           ms/op
ClientSimple.existUser                      sample  17454   1.863 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.539           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.047           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.969           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.550           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.550           ms/op
ClientSimple.getUser                        sample  15164   2.141 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.404           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.007           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.522           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.867           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.772           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.822           ms/op
ClientSimple.listUser                       sample   9033   3.550 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.108           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.600           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.007           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.122           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.122           ms/op

Benchmark result is saved to 1715215123708.json
