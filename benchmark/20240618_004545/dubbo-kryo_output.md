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
# Warmup Iteration   1: 1.818 ops/ms
Iteration   1: 7.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.148 ops/ms


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
# Warmup Iteration   1: 6.235 ops/ms
Iteration   1: 14.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.490 ops/ms


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
# Warmup Iteration   1: 4.859 ops/ms
Iteration   1: 12.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.012 ops/ms


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
# Warmup Iteration   1: 5.254 ops/ms
Iteration   1: 8.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.735 ops/ms


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.060 ms/op
Iteration   1: 2.117 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.117 ms/op


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
# Warmup Iteration   1: 2.907 ±(99.9%) 0.054 ms/op
Iteration   1: 1.807 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.807 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.064 ms/op
Iteration   1: 1.945 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.945 ms/op


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.074 ms/op
Iteration   1: 3.598 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.598 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.080 ms/op
Iteration   1: 2.475 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.277 ms/op
                 createUser·p0.90:   2.879 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  30.905 ms/op
                 createUser·p0.9999: 31.921 ms/op
                 createUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12850
  mean =      2.475 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8785 
    [ 2.500,  5.000) = 3779 
    [ 5.000,  7.500) = 118 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
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
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     30.905 ms/op
     p(99.9900) =     31.921 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 2.959 ±(99.9%) 0.069 ms/op
Iteration   1: 1.711 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   1.651 ms/op
                 existUser·p0.90:   1.886 ms/op
                 existUser·p0.95:   2.060 ms/op
                 existUser·p0.99:   2.830 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 11.118 ms/op
                 existUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18700
  mean =      1.711 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 18259 
    [ 2.500,  3.750) = 231 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      1.886 ms/op
     p(95.0000) =      2.060 ms/op
     p(99.0000) =      2.830 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     11.118 ms/op
     p(99.9990) =     11.289 ms/op
     p(99.9999) =     11.289 ms/op
    p(100.0000) =     11.289 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.087 ms/op
Iteration   1: 2.036 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   1.954 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.605 ms/op
                 getUser·p0.99:   4.233 ms/op
                 getUser·p0.999:  13.046 ms/op
                 getUser·p0.9999: 13.468 ms/op
                 getUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15712
  mean =      2.036 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 14478 
    [ 2.500,  3.750) = 912 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      4.233 ms/op
     p(99.9000) =     13.046 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.149 ms/op
Iteration   1: 3.438 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.125 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9290
  mean =      3.438 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 314 
    [ 2.500,  3.750) = 6527 
    [ 3.750,  5.000) = 2146 
    [ 5.000,  6.250) = 175 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.148          ops/ms
ClientSimple.existUser                       thrpt         14.490          ops/ms
ClientSimple.getUser                         thrpt         12.012          ops/ms
ClientSimple.listUser                        thrpt          8.735          ops/ms
ClientSimple.createUser                       avgt          2.117           ms/op
ClientSimple.existUser                        avgt          1.807           ms/op
ClientSimple.getUser                          avgt          1.945           ms/op
ClientSimple.listUser                         avgt          3.598           ms/op
ClientSimple.createUser                     sample  12850   2.475 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.603           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.277           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.166           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.159           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.905           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.921           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.949           ms/op
ClientSimple.existUser                      sample  18700   1.711 ± 0.011   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.608           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.651           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.886           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.060           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.830           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.666           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.118           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.289           ms/op
ClientSimple.getUser                        sample  15712   2.036 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.769           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.954           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.233           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.046           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.468           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.533           ms/op
ClientSimple.listUser                       sample   9290   3.438 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.378           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.125           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.225           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.055           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.088           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.088           ms/op

Benchmark result is saved to 1718671299719.json
