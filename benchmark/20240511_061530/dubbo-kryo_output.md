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
# Warmup Iteration   1: 1.806 ops/ms
Iteration   1: 6.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.818 ops/ms


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
# Warmup Iteration   1: 5.781 ops/ms
Iteration   1: 12.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.534 ops/ms
Iteration   1: 13.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.940 ops/ms


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
# Warmup Iteration   1: 5.521 ops/ms
Iteration   1: 8.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.545 ops/ms


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.077 ms/op
Iteration   1: 2.214 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.214 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.049 ms/op
Iteration   1: 1.936 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.936 ms/op


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.073 ms/op
Iteration   1: 2.028 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.028 ms/op


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
# Warmup Iteration   1: 4.492 ±(99.9%) 0.096 ms/op
Iteration   1: 3.191 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.191 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.105 ms/op
Iteration   1: 2.262 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   2.068 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   6.502 ms/op
                 createUser·p0.999:  18.313 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14134
  mean =      2.262 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 11607 
    [ 2.500,  3.750) = 2149 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      6.502 ms/op
     p(99.9000) =     18.313 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.276 ±(99.9%) 0.074 ms/op
Iteration   1: 1.999 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.402 ms/op
                 existUser·p0.50:   1.987 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.515 ms/op
                 existUser·p0.99:   3.088 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 14.257 ms/op
                 existUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15997
  mean =      1.999 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 542 
    [ 1.250,  2.500) = 14589 
    [ 2.500,  3.750) = 792 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      3.088 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     14.257 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.124 ms/op
Iteration   1: 2.112 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.009 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.888 ms/op
                 getUser·p0.99:   5.154 ms/op
                 getUser·p0.999:  18.963 ms/op
                 getUser·p0.9999: 19.972 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15140
  mean =      2.112 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 12549 
    [ 2.500,  3.750) = 2245 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      5.154 ms/op
     p(99.9000) =     18.963 ms/op
     p(99.9900) =     19.972 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.131 ms/op
Iteration   1: 3.702 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.922 ms/op
                 listUser·p0.99:   9.938 ms/op
                 listUser·p0.999:  21.889 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8643
  mean =      3.702 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 555 
    [ 2.500,  5.000) = 7688 
    [ 5.000,  7.500) = 276 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.922 ms/op
     p(99.0000) =      9.938 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.818          ops/ms
ClientSimple.existUser                       thrpt         12.766          ops/ms
ClientSimple.getUser                         thrpt         13.940          ops/ms
ClientSimple.listUser                        thrpt          8.545          ops/ms
ClientSimple.createUser                       avgt          2.214           ms/op
ClientSimple.existUser                        avgt          1.936           ms/op
ClientSimple.getUser                          avgt          2.028           ms/op
ClientSimple.listUser                         avgt          3.191           ms/op
ClientSimple.createUser                     sample  14134   2.262 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.870           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.068           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.072           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.502           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.313           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.530           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.530           ms/op
ClientSimple.existUser                      sample  15997   1.999 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.402           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.987           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.088           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.976           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.257           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.287           ms/op
ClientSimple.getUser                        sample  15140   2.112 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.667           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.009           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.154           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.963           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.972           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.988           ms/op
ClientSimple.listUser                       sample   8643   3.702 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.055           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.621           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.922           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.938           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.889           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.020           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.020           ms/op

Benchmark result is saved to 1715407855404.json
