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
# Warmup Iteration   1: 2.262 ops/ms
Iteration   1: 7.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.981 ops/ms


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
# Warmup Iteration   1: 5.307 ops/ms
Iteration   1: 11.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.465 ops/ms


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
# Warmup Iteration   1: 6.194 ops/ms
Iteration   1: 12.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.555 ops/ms


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
# Warmup Iteration   1: 5.061 ops/ms
Iteration   1: 9.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.497 ops/ms


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.081 ms/op
Iteration   1: 2.284 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.284 ms/op


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
# Warmup Iteration   1: 3.080 ±(99.9%) 0.054 ms/op
Iteration   1: 1.892 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.892 ms/op


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.071 ms/op
Iteration   1: 2.359 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.359 ms/op


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
# Warmup Iteration   1: 5.058 ±(99.9%) 0.092 ms/op
Iteration   1: 3.578 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.578 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.104 ms/op
Iteration   1: 2.043 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.429 ms/op
                 createUser·p0.50:   1.839 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   5.772 ms/op
                 createUser·p0.999:  16.597 ms/op
                 createUser·p0.9999: 17.506 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15635
  mean =      2.043 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 14127 
    [ 2.500,  3.750) = 1093 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      5.772 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     17.506 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.120 ±(99.9%) 0.091 ms/op
Iteration   1: 1.801 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   4.065 ms/op
                 existUser·p0.999:  11.784 ms/op
                 existUser·p0.9999: 14.487 ms/op
                 existUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17788
  mean =      1.801 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 686 
    [ 1.250,  2.500) = 16088 
    [ 2.500,  3.750) = 801 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      4.065 ms/op
     p(99.9000) =     11.784 ms/op
     p(99.9900) =     14.487 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.085 ms/op
Iteration   1: 2.087 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.468 ms/op
                 getUser·p0.50:   2.036 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.732 ms/op
                 getUser·p0.99:   3.187 ms/op
                 getUser·p0.999:  12.235 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15256
  mean =      2.087 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 13032 
    [ 2.500,  3.750) = 1983 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.187 ms/op
     p(99.9000) =     12.235 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     12.763 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


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
# Warmup Iteration   1: 4.546 ±(99.9%) 0.150 ms/op
Iteration   1: 3.715 ±(99.9%) 0.080 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  32.047 ms/op
                 listUser·p0.9999: 32.539 ms/op
                 listUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8605
  mean =      3.715 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 882 
    [ 2.500,  5.000) = 7455 
    [ 5.000,  7.500) = 194 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     32.047 ms/op
     p(99.9900) =     32.539 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.981          ops/ms
ClientSimple.existUser                       thrpt         11.465          ops/ms
ClientSimple.getUser                         thrpt         12.555          ops/ms
ClientSimple.listUser                        thrpt          9.497          ops/ms
ClientSimple.createUser                       avgt          2.284           ms/op
ClientSimple.existUser                        avgt          1.892           ms/op
ClientSimple.getUser                          avgt          2.359           ms/op
ClientSimple.listUser                         avgt          3.578           ms/op
ClientSimple.createUser                     sample  15635   2.043 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.429           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.839           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.772           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.597           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.506           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.727           ms/op
ClientSimple.existUser                      sample  17788   1.801 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.652           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.632           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.065           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.784           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.487           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.615           ms/op
ClientSimple.getUser                        sample  15256   2.087 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.468           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.036           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.187           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.235           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.763           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.763           ms/op
ClientSimple.listUser                       sample   8605   3.715 ± 0.080   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.847           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.604           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.455           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.047           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.539           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.539           ms/op

Benchmark result is saved to 1723140828832.json
