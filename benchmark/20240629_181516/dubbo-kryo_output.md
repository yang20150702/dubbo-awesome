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
# Warmup Iteration   1: 1.943 ops/ms
Iteration   1: 7.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.758 ops/ms


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
# Warmup Iteration   1: 6.893 ops/ms
Iteration   1: 12.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.932 ops/ms


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
# Warmup Iteration   1: 6.626 ops/ms
Iteration   1: 13.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.701 ops/ms


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
# Warmup Iteration   1: 5.174 ops/ms
Iteration   1: 8.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.593 ops/ms


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
# Warmup Iteration   1: 4.258 ±(99.9%) 0.068 ms/op
Iteration   1: 2.376 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.376 ms/op


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
# Warmup Iteration   1: 3.024 ±(99.9%) 0.052 ms/op
Iteration   1: 1.901 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.901 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.054 ms/op
Iteration   1: 2.054 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.054 ms/op


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
# Warmup Iteration   1: 4.785 ±(99.9%) 0.093 ms/op
Iteration   1: 3.628 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.628 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.072 ms/op
Iteration   1: 2.117 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   1.974 ms/op
                 createUser·p0.90:   2.609 ms/op
                 createUser·p0.95:   2.966 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  15.632 ms/op
                 createUser·p0.9999: 18.924 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15223
  mean =      2.117 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13196 
    [ 2.500,  5.000) = 1762 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     15.632 ms/op
     p(99.9900) =     18.924 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.072 ms/op
Iteration   1: 1.927 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  24.066 ms/op
                 existUser·p0.9999: 24.435 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16577
  mean =      1.927 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15764 
    [ 2.500,  5.000) = 718 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.441 ms/op
     p(99.9000) =     24.066 ms/op
     p(99.9900) =     24.435 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.085 ms/op
Iteration   1: 2.079 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   1.950 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  10.833 ms/op
                 getUser·p0.9999: 11.475 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15398
  mean =      2.079 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 195 
    [ 1.250,  2.500) = 12529 
    [ 2.500,  3.750) = 2442 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     10.833 ms/op
     p(99.9900) =     11.475 ms/op
     p(99.9990) =     11.502 ms/op
     p(99.9999) =     11.502 ms/op
    p(100.0000) =     11.502 ms/op


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.137 ms/op
Iteration   1: 3.197 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.169 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 9.929 ms/op
                 listUser·p1.00:   9.929 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9999
  mean =      3.197 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 2 
    [ 1.500,  2.000) = 10 
    [ 2.000,  2.500) = 91 
    [ 2.500,  3.000) = 4260 
    [ 3.000,  3.500) = 3830 
    [ 3.500,  4.000) = 974 
    [ 4.000,  4.500) = 533 
    [ 4.500,  5.000) = 153 
    [ 5.000,  5.500) = 89 
    [ 5.500,  6.000) = 26 
    [ 6.000,  6.500) = 10 
    [ 6.500,  7.000) = 1 
    [ 7.000,  7.500) = 1 
    [ 7.500,  8.000) = 6 
    [ 8.000,  8.500) = 2 
    [ 8.500,  9.000) = 8 
    [ 9.000,  9.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =      9.929 ms/op
     p(99.9990) =      9.929 ms/op
     p(99.9999) =      9.929 ms/op
    p(100.0000) =      9.929 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.758          ops/ms
ClientSimple.existUser                       thrpt         12.932          ops/ms
ClientSimple.getUser                         thrpt         13.701          ops/ms
ClientSimple.listUser                        thrpt          8.593          ops/ms
ClientSimple.createUser                       avgt          2.376           ms/op
ClientSimple.existUser                        avgt          1.901           ms/op
ClientSimple.getUser                          avgt          2.054           ms/op
ClientSimple.listUser                         avgt          3.628           ms/op
ClientSimple.createUser                     sample  15223   2.117 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.680           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.974           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.609           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.513           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.632           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.924           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.054           ms/op
ClientSimple.existUser                      sample  16577   1.927 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.563           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.441           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.066           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.435           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.478           ms/op
ClientSimple.getUser                        sample  15398   2.079 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.681           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.950           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.301           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.833           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.475           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.502           ms/op
ClientSimple.listUser                       sample   9999   3.197 ± 0.018   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.323           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.035           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.887           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.169           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.847           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.929           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.929           ms/op

Benchmark result is saved to 1719684670062.json
