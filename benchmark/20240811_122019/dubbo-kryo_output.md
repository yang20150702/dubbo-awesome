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
# Warmup Iteration   1: 1.483 ops/ms
Iteration   1: 6.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.712 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.585 ops/ms
Iteration   1: 12.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.955 ops/ms


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
# Warmup Iteration   1: 5.747 ops/ms
Iteration   1: 12.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.482 ops/ms


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
# Warmup Iteration   1: 4.771 ops/ms
Iteration   1: 8.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.520 ops/ms


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.066 ms/op
Iteration   1: 2.163 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.163 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.311 ±(99.9%) 0.054 ms/op
Iteration   1: 1.858 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.858 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.555 ±(99.9%) 0.060 ms/op
Iteration   1: 2.230 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.230 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.008 ±(99.9%) 0.108 ms/op
Iteration   1: 3.203 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.203 ms/op


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.099 ms/op
Iteration   1: 2.212 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.402 ms/op
                 createUser·p0.50:   1.997 ms/op
                 createUser·p0.90:   2.693 ms/op
                 createUser·p0.95:   2.937 ms/op
                 createUser·p0.99:   8.041 ms/op
                 createUser·p0.999:  24.314 ms/op
                 createUser·p0.9999: 24.736 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14444
  mean =      2.212 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11804 
    [ 2.500,  5.000) = 2414 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.693 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      8.041 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     24.736 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 3.058 ±(99.9%) 0.080 ms/op
Iteration   1: 1.867 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.515 ms/op
                 existUser·p0.99:   3.243 ms/op
                 existUser·p0.999:  12.892 ms/op
                 existUser·p0.9999: 13.177 ms/op
                 existUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17117
  mean =      1.867 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 16115 
    [ 2.500,  3.750) = 748 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      3.243 ms/op
     p(99.9000) =     12.892 ms/op
     p(99.9900) =     13.177 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 3.311 ±(99.9%) 0.097 ms/op
Iteration   1: 2.005 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   1.823 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.720 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  20.775 ms/op
                 getUser·p0.9999: 21.542 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15959
  mean =      2.005 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14516 
    [ 2.500,  5.000) = 1268 
    [ 5.000,  7.500) = 110 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     21.542 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.132 ms/op
Iteration   1: 3.323 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.517 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  28.665 ms/op
                 listUser·p0.9999: 29.721 ms/op
                 listUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9612
  mean =      3.323 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 301 
    [ 2.500,  5.000) = 9043 
    [ 5.000,  7.500) = 209 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.517 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     28.665 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.712          ops/ms
ClientSimple.existUser                       thrpt         12.955          ops/ms
ClientSimple.getUser                         thrpt         12.482          ops/ms
ClientSimple.listUser                        thrpt          8.520          ops/ms
ClientSimple.createUser                       avgt          2.163           ms/op
ClientSimple.existUser                        avgt          1.858           ms/op
ClientSimple.getUser                          avgt          2.230           ms/op
ClientSimple.listUser                         avgt          3.203           ms/op
ClientSimple.createUser                     sample  14444   2.212 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.402           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.997           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.693           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.041           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.314           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.736           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.838           ms/op
ClientSimple.existUser                      sample  17117   1.867 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.542           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.243           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.892           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.177           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.189           ms/op
ClientSimple.getUser                        sample  15959   2.005 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.675           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.823           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.898           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.775           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.542           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.561           ms/op
ClientSimple.listUser                       sample   9612   3.323 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.006           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.970           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.129           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.517           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.668           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.665           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.721           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.721           ms/op

Benchmark result is saved to 1723378576199.json
