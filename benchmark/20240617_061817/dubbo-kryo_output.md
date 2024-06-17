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
# Warmup Iteration   1: 1.603 ops/ms
Iteration   1: 8.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.178 ops/ms


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
# Warmup Iteration   1: 7.616 ops/ms
Iteration   1: 12.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.912 ops/ms


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
# Warmup Iteration   1: 6.960 ops/ms
Iteration   1: 15.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.259 ops/ms


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
# Warmup Iteration   1: 5.830 ops/ms
Iteration   1: 7.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.672 ops/ms


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.077 ms/op
Iteration   1: 2.175 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.175 ms/op


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
# Warmup Iteration   1: 3.024 ±(99.9%) 0.048 ms/op
Iteration   1: 1.740 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.740 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.069 ms/op
Iteration   1: 2.009 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.009 ms/op


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.097 ms/op
Iteration   1: 3.658 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.658 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.101 ms/op
Iteration   1: 2.312 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.519 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.880 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  15.499 ms/op
                 createUser·p0.9999: 16.883 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13817
  mean =      2.312 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 10454 
    [ 2.500,  3.750) = 2859 
    [ 3.750,  5.000) = 224 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.880 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     16.883 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 2.965 ±(99.9%) 0.083 ms/op
Iteration   1: 1.889 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   1.790 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  16.663 ms/op
                 existUser·p0.9999: 17.321 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16999
  mean =      1.889 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 16059 
    [ 2.500,  3.750) = 559 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     16.663 ms/op
     p(99.9900) =     17.321 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.083 ms/op
Iteration   1: 2.128 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.493 ms/op
                 getUser·p0.50:   1.989 ms/op
                 getUser·p0.90:   2.896 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  17.498 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15012
  mean =      2.128 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 11395 
    [ 2.500,  3.750) = 3031 
    [ 3.750,  5.000) = 187 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.123 ms/op
Iteration   1: 3.790 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.151 ms/op
                 listUser·p0.999:  10.404 ms/op
                 listUser·p0.9999: 10.502 ms/op
                 listUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8436
  mean =      3.790 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 3 
    [ 1.000,  2.000) = 73 
    [ 2.000,  3.000) = 1298 
    [ 3.000,  4.000) = 4013 
    [ 4.000,  5.000) = 2748 
    [ 5.000,  6.000) = 210 
    [ 6.000,  7.000) = 24 
    [ 7.000,  8.000) = 33 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.151 ms/op
     p(99.9000) =     10.404 ms/op
     p(99.9900) =     10.502 ms/op
     p(99.9990) =     10.502 ms/op
     p(99.9999) =     10.502 ms/op
    p(100.0000) =     10.502 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.178          ops/ms
ClientSimple.existUser                       thrpt         12.912          ops/ms
ClientSimple.getUser                         thrpt         15.259          ops/ms
ClientSimple.listUser                        thrpt          7.672          ops/ms
ClientSimple.createUser                       avgt          2.175           ms/op
ClientSimple.existUser                        avgt          1.740           ms/op
ClientSimple.getUser                          avgt          2.009           ms/op
ClientSimple.listUser                         avgt          3.658           ms/op
ClientSimple.createUser                     sample  13817   2.312 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.519           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.880           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.187           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.030           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.499           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.883           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.908           ms/op
ClientSimple.existUser                      sample  16999   1.889 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.741           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.790           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.216           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.735           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.663           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.321           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.367           ms/op
ClientSimple.getUser                        sample  15012   2.128 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.493           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.989           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.121           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.498           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.760           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.760           ms/op
ClientSimple.listUser                       sample   8436   3.790 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.745           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.781           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.891           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.151           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.404           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.502           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.502           ms/op

Benchmark result is saved to 1718604837819.json
