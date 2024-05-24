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
# Warmup Iteration   1: 1.807 ops/ms
Iteration   1: 7.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.159 ops/ms


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
# Warmup Iteration   1: 6.747 ops/ms
Iteration   1: 14.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.500 ops/ms


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
# Warmup Iteration   1: 5.971 ops/ms
Iteration   1: 13.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.647 ops/ms


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
# Warmup Iteration   1: 4.452 ops/ms
Iteration   1: 8.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.606 ops/ms


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.085 ms/op
Iteration   1: 2.285 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.285 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.044 ms/op
Iteration   1: 1.651 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.651 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.058 ms/op
Iteration   1: 1.810 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.810 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.103 ms/op
Iteration   1: 2.964 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.964 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.289 ±(99.9%) 0.079 ms/op
Iteration   1: 2.281 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.013 ms/op
                 createUser·p0.90:   2.781 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   6.184 ms/op
                 createUser·p0.999:  25.330 ms/op
                 createUser·p0.9999: 27.203 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14005
  mean =      2.281 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10879 
    [ 2.500,  5.000) = 2892 
    [ 5.000,  7.500) = 135 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      6.184 ms/op
     p(99.9000) =     25.330 ms/op
     p(99.9900) =     27.203 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.067 ms/op
Iteration   1: 1.826 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.187 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   4.333 ms/op
                 existUser·p0.999:  13.869 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17508
  mean =      1.826 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 16550 
    [ 2.500,  3.750) = 647 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.187 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      4.333 ms/op
     p(99.9000) =     13.869 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.092 ms/op
Iteration   1: 2.110 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   1.976 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   4.012 ms/op
                 getUser·p0.999:  22.610 ms/op
                 getUser·p0.9999: 33.883 ms/op
                 getUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15157
  mean =      2.110 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12964 
    [ 2.500,  5.000) = 2121 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      4.012 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     33.883 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 4.963 ±(99.9%) 0.168 ms/op
Iteration   1: 3.274 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.395 ms/op
                 listUser·p0.999:  14.862 ms/op
                 listUser·p0.9999: 16.007 ms/op
                 listUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9766
  mean =      3.274 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 387 
    [ 2.500,  3.750) = 7455 
    [ 3.750,  5.000) = 1722 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.395 ms/op
     p(99.9000) =     14.862 ms/op
     p(99.9900) =     16.007 ms/op
     p(99.9990) =     16.007 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.159          ops/ms
ClientSimple.existUser                       thrpt         14.500          ops/ms
ClientSimple.getUser                         thrpt         13.647          ops/ms
ClientSimple.listUser                        thrpt          8.606          ops/ms
ClientSimple.createUser                       avgt          2.285           ms/op
ClientSimple.existUser                        avgt          1.651           ms/op
ClientSimple.getUser                          avgt          1.810           ms/op
ClientSimple.listUser                         avgt          2.964           ms/op
ClientSimple.createUser                     sample  14005   2.281 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.879           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.013           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.072           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.184           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.330           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.203           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.623           ms/op
ClientSimple.existUser                      sample  17508   1.826 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.717           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.690           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.187           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.333           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.869           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.959           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.959           ms/op
ClientSimple.getUser                        sample  15157   2.110 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.696           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.976           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.012           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.610           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         33.883           ms/op
ClientSimple.getUser:getUser·p1.00          sample         34.931           ms/op
ClientSimple.listUser                       sample   9766   3.274 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.395           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.862           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.007           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.007           ms/op

Benchmark result is saved to 1716511176436.json
