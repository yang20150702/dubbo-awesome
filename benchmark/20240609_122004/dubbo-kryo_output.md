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
# Warmup Iteration   1: 1.649 ops/ms
Iteration   1: 7.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.942 ops/ms


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
# Warmup Iteration   1: 6.065 ops/ms
Iteration   1: 12.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.941 ops/ms


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
# Warmup Iteration   1: 5.537 ops/ms
Iteration   1: 13.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.791 ops/ms


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
# Warmup Iteration   1: 4.965 ops/ms
Iteration   1: 8.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.103 ops/ms


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.084 ms/op
Iteration   1: 2.429 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.429 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.060 ms/op
Iteration   1: 1.867 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.867 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.052 ms/op
Iteration   1: 2.088 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.088 ms/op


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.087 ms/op
Iteration   1: 3.257 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.257 ms/op


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.111 ms/op
Iteration   1: 2.244 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   2.058 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   7.705 ms/op
                 createUser·p0.999:  26.895 ms/op
                 createUser·p0.9999: 28.792 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14244
  mean =      2.244 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11332 
    [ 2.500,  5.000) = 2743 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      7.705 ms/op
     p(99.9000) =     26.895 ms/op
     p(99.9900) =     28.792 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.084 ms/op
Iteration   1: 1.932 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.654 ms/op
                 existUser·p0.95:   2.933 ms/op
                 existUser·p0.99:   3.692 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 12.392 ms/op
                 existUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16780
  mean =      1.932 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 777 
    [ 1.250,  2.500) = 13651 
    [ 2.500,  3.750) = 2187 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      3.692 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     12.392 ms/op
     p(99.9990) =     12.403 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


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
# Warmup Iteration   1: 3.496 ±(99.9%) 0.096 ms/op
Iteration   1: 2.105 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.505 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.802 ms/op
                 getUser·p0.99:   4.298 ms/op
                 getUser·p0.999:  13.091 ms/op
                 getUser·p0.9999: 13.270 ms/op
                 getUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15216
  mean =      2.105 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 13046 
    [ 2.500,  3.750) = 1862 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.298 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     13.270 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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
# Warmup Iteration   1: 4.901 ±(99.9%) 0.187 ms/op
Iteration   1: 3.326 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.628 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9623
  mean =      3.326 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 226 
    [ 2.500,  3.750) = 7171 
    [ 3.750,  5.000) = 1903 
    [ 5.000,  6.250) = 201 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.628 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.942          ops/ms
ClientSimple.existUser                       thrpt         12.941          ops/ms
ClientSimple.getUser                         thrpt         13.791          ops/ms
ClientSimple.listUser                        thrpt          8.103          ops/ms
ClientSimple.createUser                       avgt          2.429           ms/op
ClientSimple.existUser                        avgt          1.867           ms/op
ClientSimple.getUser                          avgt          2.088           ms/op
ClientSimple.listUser                         avgt          3.257           ms/op
ClientSimple.createUser                     sample  14244   2.244 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.459           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.058           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.072           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.705           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.895           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.792           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.098           ms/op
ClientSimple.existUser                      sample  16780   1.932 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.575           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.933           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.692           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.255           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.392           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.403           ms/op
ClientSimple.getUser                        sample  15216   2.105 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.505           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.298           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.091           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.270           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.287           ms/op
ClientSimple.listUser                       sample   9623   3.326 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.947           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.006           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.628           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.269           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.679           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.679           ms/op

Benchmark result is saved to 1717935340104.json
