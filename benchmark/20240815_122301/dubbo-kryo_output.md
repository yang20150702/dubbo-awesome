# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.783 ops/ms
Iteration   1: 7.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.087 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.904 ops/ms
Iteration   1: 12.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.285 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.992 ops/ms
Iteration   1: 12.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.723 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.017 ops/ms
Iteration   1: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.425 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.714 ±(99.9%) 0.091 ms/op
Iteration   1: 2.133 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.295 ±(99.9%) 0.048 ms/op
Iteration   1: 1.908 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.908 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.321 ±(99.9%) 0.056 ms/op
Iteration   1: 2.120 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.120 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.638 ±(99.9%) 0.090 ms/op
Iteration   1: 3.586 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.586 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.580 ±(99.9%) 0.089 ms/op
Iteration   1: 2.440 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.055 ms/op
                 createUser·p0.99:   7.640 ms/op
                 createUser·p0.999:  44.719 ms/op
                 createUser·p0.9999: 46.531 ms/op
                 createUser·p1.00:   46.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13321
  mean =      2.440 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13061 
    [ 5.000, 10.000) = 132 
    [10.000, 15.000) = 64 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.055 ms/op
     p(99.0000) =      7.640 ms/op
     p(99.9000) =     44.719 ms/op
     p(99.9900) =     46.531 ms/op
     p(99.9990) =     46.596 ms/op
     p(99.9999) =     46.596 ms/op
    p(100.0000) =     46.596 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.953 ±(99.9%) 0.064 ms/op
Iteration   1: 1.937 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.360 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.580 ms/op
                 existUser·p0.95:   2.830 ms/op
                 existUser·p0.99:   4.570 ms/op
                 existUser·p0.999:  11.674 ms/op
                 existUser·p0.9999: 12.042 ms/op
                 existUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16503
  mean =      1.937 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 413 
    [ 1.250,  2.500) = 14187 
    [ 2.500,  3.750) = 1667 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      4.570 ms/op
     p(99.9000) =     11.674 ms/op
     p(99.9900) =     12.042 ms/op
     p(99.9990) =     12.042 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.095 ms/op
Iteration   1: 2.100 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   1.978 ms/op
                 getUser·p0.90:   2.644 ms/op
                 getUser·p0.95:   3.044 ms/op
                 getUser·p0.99:   4.259 ms/op
                 getUser·p0.999:  13.289 ms/op
                 getUser·p0.9999: 13.912 ms/op
                 getUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15234
  mean =      2.100 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 13325 
    [ 2.500,  3.750) = 1652 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.644 ms/op
     p(95.0000) =      3.044 ms/op
     p(99.0000) =      4.259 ms/op
     p(99.9000) =     13.289 ms/op
     p(99.9900) =     13.912 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.612 ±(99.9%) 0.124 ms/op
Iteration   1: 3.742 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  17.939 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8554
  mean =      3.742 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 373 
    [ 2.500,  3.750) = 4164 
    [ 3.750,  5.000) = 3718 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     17.939 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.087          ops/ms
ClientSimple.existUser                       thrpt         12.285          ops/ms
ClientSimple.getUser                         thrpt         12.723          ops/ms
ClientSimple.listUser                        thrpt          8.425          ops/ms
ClientSimple.createUser                       avgt          2.133           ms/op
ClientSimple.existUser                        avgt          1.908           ms/op
ClientSimple.getUser                          avgt          2.120           ms/op
ClientSimple.listUser                         avgt          3.586           ms/op
ClientSimple.createUser                     sample  13321   2.440 ± 0.068   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.631           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.055           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.640           ms/op
ClientSimple.createUser:createUser·p0.999   sample         44.719           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         46.531           ms/op
ClientSimple.createUser:createUser·p1.00    sample         46.596           ms/op
ClientSimple.existUser                      sample  16503   1.937 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.360           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.830           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.570           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.674           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.042           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.042           ms/op
ClientSimple.getUser                        sample  15234   2.100 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.915           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.978           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.644           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.044           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.259           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.289           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.912           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.057           ms/op
ClientSimple.listUser                       sample   8554   3.742 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.941           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.595           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.939           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.219           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.219           ms/op

Benchmark result is saved to 1723724297480.json
