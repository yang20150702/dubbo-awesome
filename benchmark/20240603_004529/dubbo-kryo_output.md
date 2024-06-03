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
# Warmup Iteration   1: 1.983 ops/ms
Iteration   1: 6.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.943 ops/ms


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
# Warmup Iteration   1: 6.765 ops/ms
Iteration   1: 14.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.738 ops/ms
Iteration   1: 13.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.181 ops/ms


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
# Warmup Iteration   1: 5.212 ops/ms
Iteration   1: 8.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.480 ops/ms


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.060 ms/op
Iteration   1: 2.163 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.163 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.065 ms/op
Iteration   1: 2.096 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.096 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.066 ms/op
Iteration   1: 1.997 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.997 ms/op


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.109 ms/op
Iteration   1: 3.286 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.286 ms/op


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.105 ms/op
Iteration   1: 2.107 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.499 ms/op
                 createUser·p0.50:   1.944 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.707 ms/op
                 createUser·p0.99:   5.221 ms/op
                 createUser·p0.999:  35.062 ms/op
                 createUser·p0.9999: 41.091 ms/op
                 createUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15164
  mean =      2.107 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15000 
    [ 5.000, 10.000) = 132 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      5.221 ms/op
     p(99.9000) =     35.062 ms/op
     p(99.9900) =     41.091 ms/op
     p(99.9990) =     41.091 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.081 ms/op
Iteration   1: 1.993 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.256 ms/op
                 existUser·p0.50:   1.831 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  31.705 ms/op
                 existUser·p0.9999: 34.149 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16429
  mean =      1.993 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15400 
    [ 2.500,  5.000) = 925 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.256 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =     31.705 ms/op
     p(99.9900) =     34.149 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.073 ms/op
Iteration   1: 2.292 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.489 ms/op
                 getUser·p0.50:   2.277 ms/op
                 getUser·p0.90:   2.843 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   3.787 ms/op
                 getUser·p0.999:  11.578 ms/op
                 getUser·p0.9999: 11.773 ms/op
                 getUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14321
  mean =      2.292 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 227 
    [ 1.250,  2.500) = 9924 
    [ 2.500,  3.750) = 4025 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.843 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.787 ms/op
     p(99.9000) =     11.578 ms/op
     p(99.9900) =     11.773 ms/op
     p(99.9990) =     11.829 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.133 ms/op
Iteration   1: 3.467 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.389 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  18.244 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9222
  mean =      3.467 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 894 
    [ 2.500,  3.750) = 5902 
    [ 3.750,  5.000) = 1998 
    [ 5.000,  6.250) = 199 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.389 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     18.244 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.943          ops/ms
ClientSimple.existUser                       thrpt         14.862          ops/ms
ClientSimple.getUser                         thrpt         13.181          ops/ms
ClientSimple.listUser                        thrpt          8.480          ops/ms
ClientSimple.createUser                       avgt          2.163           ms/op
ClientSimple.existUser                        avgt          2.096           ms/op
ClientSimple.getUser                          avgt          1.997           ms/op
ClientSimple.listUser                         avgt          3.286           ms/op
ClientSimple.createUser                     sample  15164   2.107 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.499           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.944           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.221           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.062           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         41.091           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.091           ms/op
ClientSimple.existUser                      sample  16429   1.993 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.256           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.831           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.977           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.705           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.149           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.275           ms/op
ClientSimple.getUser                        sample  14321   2.292 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.489           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.843           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.039           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.787           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.578           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.773           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.829           ms/op
ClientSimple.listUser                       sample   9222   3.467 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.116           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.389           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.012           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.244           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.038           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.038           ms/op

Benchmark result is saved to 1717375268791.json
