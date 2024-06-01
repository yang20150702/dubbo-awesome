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
# Warmup Iteration   1: 1.771 ops/ms
Iteration   1: 7.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.146 ops/ms


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
# Warmup Iteration   1: 5.923 ops/ms
Iteration   1: 14.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.427 ops/ms


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
# Warmup Iteration   1: 6.133 ops/ms
Iteration   1: 14.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.862 ops/ms


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
# Warmup Iteration   1: 5.860 ops/ms
Iteration   1: 7.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.772 ops/ms


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.094 ms/op
Iteration   1: 2.267 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.267 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.046 ms/op
Iteration   1: 2.089 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.089 ms/op


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
# Warmup Iteration   1: 3.181 ±(99.9%) 0.065 ms/op
Iteration   1: 2.168 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.168 ms/op


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
# Warmup Iteration   1: 4.292 ±(99.9%) 0.099 ms/op
Iteration   1: 3.275 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.275 ms/op


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
# Warmup Iteration   1: 3.510 ±(99.9%) 0.081 ms/op
Iteration   1: 2.099 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   1.966 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.769 ms/op
                 createUser·p0.99:   3.742 ms/op
                 createUser·p0.999:  29.468 ms/op
                 createUser·p0.9999: 35.463 ms/op
                 createUser·p1.00:   41.157 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15568
  mean =      2.099 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15480 
    [ 5.000, 10.000) = 16 
    [10.000, 15.000) = 28 
    [15.000, 20.000) = 12 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 24 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      3.742 ms/op
     p(99.9000) =     29.468 ms/op
     p(99.9900) =     35.463 ms/op
     p(99.9990) =     41.157 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.081 ms/op
Iteration   1: 1.747 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.416 ms/op
                 existUser·p0.50:   1.577 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   3.064 ms/op
                 existUser·p0.999:  21.576 ms/op
                 existUser·p0.9999: 21.969 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18566
  mean =      1.747 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17215 
    [ 2.500,  5.000) = 1272 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      1.577 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.064 ms/op
     p(99.9000) =     21.576 ms/op
     p(99.9900) =     21.969 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.088 ms/op
Iteration   1: 2.157 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   2.075 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.945 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  13.814 ms/op
                 getUser·p0.9999: 14.699 ms/op
                 getUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14831
  mean =      2.157 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 11250 
    [ 2.500,  3.750) = 3213 
    [ 3.750,  5.000) = 151 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =     13.814 ms/op
     p(99.9900) =     14.699 ms/op
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
# Warmup Iteration   1: 6.104 ±(99.9%) 0.213 ms/op
Iteration   1: 3.647 ±(99.9%) 0.072 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.371 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   10.928 ms/op
                 listUser·p0.999:  32.997 ms/op
                 listUser·p0.9999: 34.079 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8791
  mean =      3.647 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 348 
    [ 2.500,  5.000) = 8107 
    [ 5.000,  7.500) = 202 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     32.997 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.146          ops/ms
ClientSimple.existUser                       thrpt         14.427          ops/ms
ClientSimple.getUser                         thrpt         14.862          ops/ms
ClientSimple.listUser                        thrpt          7.772          ops/ms
ClientSimple.createUser                       avgt          2.267           ms/op
ClientSimple.existUser                        avgt          2.089           ms/op
ClientSimple.getUser                          avgt          2.168           ms/op
ClientSimple.listUser                         avgt          3.275           ms/op
ClientSimple.createUser                     sample  15568   2.099 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.680           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.966           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.742           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.468           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.463           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.157           ms/op
ClientSimple.existUser                      sample  18566   1.747 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.416           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.577           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.064           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.576           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.969           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.053           ms/op
ClientSimple.getUser                        sample  14831   2.157 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.622           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.075           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.945           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.284           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.814           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.699           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.762           ms/op
ClientSimple.listUser                       sample   8791   3.647 ± 0.072   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.047           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.371           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.928           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.997           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         34.079           ms/op
ClientSimple.listUser:listUser·p1.00        sample         34.079           ms/op

Benchmark result is saved to 1717202573823.json
