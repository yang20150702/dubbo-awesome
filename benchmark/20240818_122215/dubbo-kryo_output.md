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
# Warmup Iteration   1: 1.637 ops/ms
Iteration   1: 6.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.349 ops/ms


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
# Warmup Iteration   1: 5.345 ops/ms
Iteration   1: 12.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.561 ops/ms


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
# Warmup Iteration   1: 4.430 ops/ms
Iteration   1: 11.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.740 ops/ms


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
# Warmup Iteration   1: 5.790 ops/ms
Iteration   1: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.129 ops/ms


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
# Warmup Iteration   1: 4.646 ±(99.9%) 0.134 ms/op
Iteration   1: 2.484 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.484 ms/op


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
# Warmup Iteration   1: 2.908 ±(99.9%) 0.050 ms/op
Iteration   1: 1.838 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.838 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.049 ms/op
Iteration   1: 1.921 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.921 ms/op


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.073 ms/op
Iteration   1: 3.732 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.732 ms/op


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.139 ms/op
Iteration   1: 2.187 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.535 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   7.530 ms/op
                 createUser·p0.999:  18.264 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14611
  mean =      2.187 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 12933 
    [ 2.500,  3.750) = 1253 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      7.530 ms/op
     p(99.9000) =     18.264 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.078 ms/op
Iteration   1: 2.414 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.302 ms/op
                 existUser·p0.90:   2.740 ms/op
                 existUser·p0.95:   2.903 ms/op
                 existUser·p0.99:   5.087 ms/op
                 existUser·p0.999:  26.698 ms/op
                 existUser·p0.9999: 27.099 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13246
  mean =      2.414 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9220 
    [ 2.500,  5.000) = 3871 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.302 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.903 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =     26.698 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 3.389 ±(99.9%) 0.078 ms/op
Iteration   1: 2.366 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.340 ms/op
                 getUser·p0.50:   2.355 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.025 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 12.915 ms/op
                 getUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13525
  mean =      2.366 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 8222 
    [ 2.500,  3.750) = 4942 
    [ 3.750,  5.000) = 148 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.340 ms/op
     p(50.0000) =      2.355 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      4.025 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     12.915 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.138 ms/op
Iteration   1: 3.330 ±(99.9%) 0.063 ms/op
                 listUser·p0.00:   0.658 ms/op
                 listUser·p0.50:   3.125 ms/op
                 listUser·p0.90:   4.239 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.057 ms/op
                 listUser·p0.999:  31.556 ms/op
                 listUser·p0.9999: 31.949 ms/op
                 listUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9625
  mean =      3.330 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2188 
    [ 2.500,  5.000) = 7079 
    [ 5.000,  7.500) = 264 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
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
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      4.239 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.057 ms/op
     p(99.9000) =     31.556 ms/op
     p(99.9900) =     31.949 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.349          ops/ms
ClientSimple.existUser                       thrpt         12.561          ops/ms
ClientSimple.getUser                         thrpt         11.740          ops/ms
ClientSimple.listUser                        thrpt          8.129          ops/ms
ClientSimple.createUser                       avgt          2.484           ms/op
ClientSimple.existUser                        avgt          1.838           ms/op
ClientSimple.getUser                          avgt          1.921           ms/op
ClientSimple.listUser                         avgt          3.732           ms/op
ClientSimple.createUser                     sample  14611   2.187 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.879           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.530           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.264           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.743           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.743           ms/op
ClientSimple.existUser                      sample  13246   2.414 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.652           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.903           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.087           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.698           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.099           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.099           ms/op
ClientSimple.getUser                        sample  13525   2.366 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.340           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.273           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.025           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.288           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.915           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.927           ms/op
ClientSimple.listUser                       sample   9625   3.330 ± 0.063   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.658           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.125           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.239           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.057           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.556           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.949           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.949           ms/op

Benchmark result is saved to 1723983466589.json
