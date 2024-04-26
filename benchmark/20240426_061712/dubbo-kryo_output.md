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
# Warmup Iteration   1: 1.336 ops/ms
Iteration   1: 6.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.029 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 6.805 ops/ms
Iteration   1: 13.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.438 ops/ms


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
# Warmup Iteration   1: 5.477 ops/ms
Iteration   1: 12.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.766 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.489 ops/ms
Iteration   1: 8.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.781 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.051 ±(99.9%) 0.085 ms/op
Iteration   1: 2.515 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.515 ms/op


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.076 ms/op
Iteration   1: 2.014 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.014 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.074 ms/op
Iteration   1: 2.171 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.171 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.097 ms/op
Iteration   1: 3.218 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.218 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.096 ms/op
Iteration   1: 2.325 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   1.939 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.346 ms/op
                 createUser·p0.99:   10.394 ms/op
                 createUser·p0.999:  22.118 ms/op
                 createUser·p0.9999: 31.625 ms/op
                 createUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13758
  mean =      2.325 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10677 
    [ 2.500,  5.000) = 2877 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.346 ms/op
     p(99.0000) =     10.394 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     31.625 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.075 ms/op
Iteration   1: 1.841 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   3.194 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 12.734 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17536
  mean =      1.841 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 813 
    [ 1.250,  2.500) = 15873 
    [ 2.500,  3.750) = 718 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.194 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     12.734 ms/op
     p(99.9990) =     12.747 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.103 ms/op
Iteration   1: 2.041 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.769 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   4.060 ms/op
                 getUser·p0.999:  23.035 ms/op
                 getUser·p0.9999: 24.751 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15671
  mean =      2.041 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12717 
    [ 2.500,  5.000) = 2860 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      4.060 ms/op
     p(99.9000) =     23.035 ms/op
     p(99.9900) =     24.751 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 5.924 ±(99.9%) 0.154 ms/op
Iteration   1: 3.780 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.001 ms/op
                 listUser·p0.9999: 15.860 ms/op
                 listUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8433
  mean =      3.780 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 196 
    [ 2.500,  3.750) = 4379 
    [ 3.750,  5.000) = 3293 
    [ 5.000,  6.250) = 405 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     15.001 ms/op
     p(99.9900) =     15.860 ms/op
     p(99.9990) =     15.860 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.029          ops/ms
ClientSimple.existUser                       thrpt         13.438          ops/ms
ClientSimple.getUser                         thrpt         12.766          ops/ms
ClientSimple.listUser                        thrpt          8.781          ops/ms
ClientSimple.createUser                       avgt          2.515           ms/op
ClientSimple.existUser                        avgt          2.014           ms/op
ClientSimple.getUser                          avgt          2.171           ms/op
ClientSimple.listUser                         avgt          3.218           ms/op
ClientSimple.createUser                     sample  13758   2.325 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.906           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.939           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.346           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.394           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.118           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.625           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.687           ms/op
ClientSimple.existUser                      sample  17536   1.841 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.518           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.194           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.534           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.734           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.747           ms/op
ClientSimple.getUser                        sample  15671   2.041 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.656           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.060           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.035           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.751           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.936           ms/op
ClientSimple.listUser                       sample   8433   3.780 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.962           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.682           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.251           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.242           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.001           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.860           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.860           ms/op

Benchmark result is saved to 1714111976121.json
