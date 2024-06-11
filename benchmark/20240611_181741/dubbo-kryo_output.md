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
# Warmup Iteration   1: 1.498 ops/ms
Iteration   1: 6.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.523 ops/ms


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
# Warmup Iteration   1: 6.312 ops/ms
Iteration   1: 12.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.067 ops/ms


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
# Warmup Iteration   1: 5.066 ops/ms
Iteration   1: 12.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.308 ops/ms


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
# Warmup Iteration   1: 4.350 ops/ms
Iteration   1: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.047 ops/ms


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.082 ms/op
Iteration   1: 2.196 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.196 ms/op


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
# Warmup Iteration   1: 3.158 ±(99.9%) 0.051 ms/op
Iteration   1: 1.821 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.821 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.056 ms/op
Iteration   1: 2.251 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.251 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.082 ms/op
Iteration   1: 3.697 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.697 ms/op


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.098 ms/op
Iteration   1: 2.275 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   2.179 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.865 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  21.822 ms/op
                 createUser·p0.9999: 25.106 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14050
  mean =      2.275 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11486 
    [ 2.500,  5.000) = 2381 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.865 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     21.822 ms/op
     p(99.9900) =     25.106 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.075 ms/op
Iteration   1: 2.084 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   1.823 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   4.279 ms/op
                 existUser·p0.999:  10.813 ms/op
                 existUser·p0.9999: 11.247 ms/op
                 existUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15363
  mean =      2.084 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 12234 
    [ 2.500,  3.750) = 2910 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      4.279 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     11.247 ms/op
     p(99.9990) =     11.256 ms/op
     p(99.9999) =     11.256 ms/op
    p(100.0000) =     11.256 ms/op


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
# Warmup Iteration   1: 3.515 ±(99.9%) 0.092 ms/op
Iteration   1: 2.179 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.818 ms/op
                 getUser·p0.95:   3.048 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  11.174 ms/op
                 getUser·p0.9999: 11.461 ms/op
                 getUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14794
  mean =      2.179 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 11317 
    [ 2.500,  3.750) = 3182 
    [ 3.750,  5.000) = 175 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.048 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     11.174 ms/op
     p(99.9900) =     11.461 ms/op
     p(99.9990) =     11.469 ms/op
     p(99.9999) =     11.469 ms/op
    p(100.0000) =     11.469 ms/op


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.134 ms/op
Iteration   1: 3.247 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   3.146 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.745 ms/op
                 listUser·p0.999:  8.751 ms/op
                 listUser·p0.9999: 10.994 ms/op
                 listUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9870
  mean =      3.247 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 981 
    [ 2.500,  3.750) = 6703 
    [ 3.750,  5.000) = 1964 
    [ 5.000,  6.250) = 134 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.745 ms/op
     p(99.9000) =      8.751 ms/op
     p(99.9900) =     10.994 ms/op
     p(99.9990) =     10.994 ms/op
     p(99.9999) =     10.994 ms/op
    p(100.0000) =     10.994 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.523          ops/ms
ClientSimple.existUser                       thrpt         12.067          ops/ms
ClientSimple.getUser                         thrpt         12.308          ops/ms
ClientSimple.listUser                        thrpt          8.047          ops/ms
ClientSimple.createUser                       avgt          2.196           ms/op
ClientSimple.existUser                        avgt          1.821           ms/op
ClientSimple.getUser                          avgt          2.251           ms/op
ClientSimple.listUser                         avgt          3.697           ms/op
ClientSimple.createUser                     sample  14050   2.275 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.763           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.179           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.865           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.751           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.822           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.106           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.199           ms/op
ClientSimple.existUser                      sample  15363   2.084 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.978           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.823           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.871           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.084           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.279           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.813           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.247           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.256           ms/op
ClientSimple.getUser                        sample  14794   2.179 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.767           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.048           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.301           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.174           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.461           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.469           ms/op
ClientSimple.listUser                       sample   9870   3.247 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.772           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.146           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.745           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.751           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.994           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.994           ms/op

Benchmark result is saved to 1718129584755.json
