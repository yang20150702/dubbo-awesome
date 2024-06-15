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
# Warmup Iteration   1: 1.748 ops/ms
Iteration   1: 6.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.369 ops/ms


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
# Warmup Iteration   1: 5.395 ops/ms
Iteration   1: 11.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.224 ops/ms


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
# Warmup Iteration   1: 5.017 ops/ms
Iteration   1: 12.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.248 ops/ms


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
# Warmup Iteration   1: 5.936 ops/ms
Iteration   1: 8.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.677 ops/ms


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.063 ms/op
Iteration   1: 2.249 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.249 ms/op


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
# Warmup Iteration   1: 3.428 ±(99.9%) 0.044 ms/op
Iteration   1: 1.829 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.829 ms/op


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
# Warmup Iteration   1: 3.229 ±(99.9%) 0.063 ms/op
Iteration   1: 1.973 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.973 ms/op


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.100 ms/op
Iteration   1: 3.269 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.269 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.101 ms/op
Iteration   1: 1.960 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   1.747 ms/op
                 createUser·p0.90:   2.503 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   5.777 ms/op
                 createUser·p0.999:  27.492 ms/op
                 createUser·p0.9999: 31.261 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16325
  mean =      1.960 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14691 
    [ 2.500,  5.000) = 1421 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      5.777 ms/op
     p(99.9000) =     27.492 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 2.811 ±(99.9%) 0.060 ms/op
Iteration   1: 1.681 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   1.563 ms/op
                 existUser·p0.90:   2.150 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   2.937 ms/op
                 existUser·p0.999:  29.393 ms/op
                 existUser·p0.9999: 29.474 ms/op
                 existUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19028
  mean =      1.681 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18468 
    [ 2.500,  5.000) = 487 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      1.563 ms/op
     p(90.0000) =      2.150 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      2.937 ms/op
     p(99.9000) =     29.393 ms/op
     p(99.9900) =     29.474 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 3.114 ±(99.9%) 0.074 ms/op
Iteration   1: 2.019 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.278 ms/op
                 getUser·p0.50:   1.829 ms/op
                 getUser·p0.90:   2.822 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 12.675 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15885
  mean =      2.019 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1757 
    [ 1.250,  2.500) = 10612 
    [ 2.500,  3.750) = 3208 
    [ 3.750,  5.000) = 147 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.278 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     12.675 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.132 ms/op
Iteration   1: 3.158 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   3.117 ms/op
                 listUser·p0.90:   4.070 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  13.384 ms/op
                 listUser·p0.9999: 14.024 ms/op
                 listUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10122
  mean =      3.158 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2692 
    [ 2.500,  3.750) = 5098 
    [ 3.750,  5.000) = 2090 
    [ 5.000,  6.250) = 192 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      4.070 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     13.384 ms/op
     p(99.9900) =     14.024 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.369          ops/ms
ClientSimple.existUser                       thrpt         11.224          ops/ms
ClientSimple.getUser                         thrpt         12.248          ops/ms
ClientSimple.listUser                        thrpt          8.677          ops/ms
ClientSimple.createUser                       avgt          2.249           ms/op
ClientSimple.existUser                        avgt          1.829           ms/op
ClientSimple.getUser                          avgt          1.973           ms/op
ClientSimple.listUser                         avgt          3.269           ms/op
ClientSimple.createUser                     sample  16325   1.960 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.606           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.747           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.503           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.777           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.492           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.261           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.261           ms/op
ClientSimple.existUser                      sample  19028   1.681 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.652           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.563           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.937           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.393           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.474           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.622           ms/op
ClientSimple.getUser                        sample  15885   2.019 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.278           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.829           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.084           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.087           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.452           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.675           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.878           ms/op
ClientSimple.listUser                       sample  10122   3.158 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.790           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.117           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.070           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.849           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.384           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.024           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.025           ms/op

Benchmark result is saved to 1718475110038.json
