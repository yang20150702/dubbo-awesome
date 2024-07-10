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
# Warmup Iteration   1: 1.887 ops/ms
Iteration   1: 6.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.330 ops/ms


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
# Warmup Iteration   1: 5.664 ops/ms
Iteration   1: 12.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.444 ops/ms


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
# Warmup Iteration   1: 5.367 ops/ms
Iteration   1: 12.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.750 ops/ms


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
# Warmup Iteration   1: 4.516 ops/ms
Iteration   1: 8.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.848 ops/ms


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.086 ms/op
Iteration   1: 2.275 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.275 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.049 ms/op
Iteration   1: 1.869 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.869 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.067 ms/op
Iteration   1: 2.073 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.073 ms/op


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
# Warmup Iteration   1: 5.013 ±(99.9%) 0.111 ms/op
Iteration   1: 3.652 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.652 ms/op


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.111 ms/op
Iteration   1: 2.529 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   2.175 ms/op
                 createUser·p0.90:   2.810 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   11.911 ms/op
                 createUser·p0.999:  35.914 ms/op
                 createUser·p0.9999: 36.880 ms/op
                 createUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12632
  mean =      2.529 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9872 
    [ 2.500,  5.000) = 2408 
    [ 5.000,  7.500) = 119 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =     11.911 ms/op
     p(99.9000) =     35.914 ms/op
     p(99.9900) =     36.880 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.077 ms/op
Iteration   1: 1.843 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   3.536 ms/op
                 existUser·p0.999:  19.169 ms/op
                 existUser·p0.9999: 21.482 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17386
  mean =      1.843 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16557 
    [ 2.500,  5.000) = 736 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.536 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     21.482 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 3.457 ±(99.9%) 0.105 ms/op
Iteration   1: 1.855 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   1.719 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.580 ms/op
                 getUser·p0.99:   3.227 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 14.715 ms/op
                 getUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17220
  mean =      1.855 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 371 
    [ 1.250,  2.500) = 15719 
    [ 2.500,  3.750) = 1024 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      1.719 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.227 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     14.715 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.140 ms/op
Iteration   1: 3.402 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.215 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.087 ms/op
                 listUser·p0.999:  20.808 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9396
  mean =      3.402 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 929 
    [ 2.500,  5.000) = 8122 
    [ 5.000,  7.500) = 310 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.330          ops/ms
ClientSimple.existUser                       thrpt         12.444          ops/ms
ClientSimple.getUser                         thrpt         12.750          ops/ms
ClientSimple.listUser                        thrpt          8.848          ops/ms
ClientSimple.createUser                       avgt          2.275           ms/op
ClientSimple.existUser                        avgt          1.869           ms/op
ClientSimple.getUser                          avgt          2.073           ms/op
ClientSimple.listUser                         avgt          3.652           ms/op
ClientSimple.createUser                     sample  12632   2.529 ± 0.075   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.424           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.175           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.617           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.911           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.914           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.880           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.897           ms/op
ClientSimple.existUser                      sample  17386   1.843 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.568           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.683           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.536           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.169           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.482           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.741           ms/op
ClientSimple.getUser                        sample  17220   1.855 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.741           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.719           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.227           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.107           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.715           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.762           ms/op
ClientSimple.listUser                       sample   9396   3.402 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.352           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.215           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.087           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.808           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.939           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.939           ms/op

Benchmark result is saved to 1720572149581.json
