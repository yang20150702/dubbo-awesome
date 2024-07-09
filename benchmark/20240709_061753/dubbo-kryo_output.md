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
# Warmup Iteration   1: 0.711 ops/ms
Iteration   1: 5.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.270 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ops/ms
Iteration   1: 12.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.343 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.646 ops/ms
Iteration   1: 13.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.252 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.826 ops/ms
Iteration   1: 8.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.430 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ±(99.9%) 0.077 ms/op
Iteration   1: 2.169 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.169 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.050 ms/op
Iteration   1: 1.906 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.906 ms/op


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
# Warmup Iteration   1: 3.238 ±(99.9%) 0.055 ms/op
Iteration   1: 1.862 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.862 ms/op


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.095 ms/op
Iteration   1: 3.481 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.481 ms/op


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.114 ms/op
Iteration   1: 2.161 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   1.901 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  20.323 ms/op
                 createUser·p0.9999: 20.890 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14797
  mean =      2.161 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12828 
    [ 2.500,  5.000) = 1795 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     20.323 ms/op
     p(99.9900) =     20.890 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 3.697 ±(99.9%) 0.101 ms/op
Iteration   1: 1.880 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.410 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.170 ms/op
                 existUser·p0.999:  12.190 ms/op
                 existUser·p0.9999: 12.481 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16999
  mean =      1.880 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 534 
    [ 1.250,  2.500) = 15469 
    [ 2.500,  3.750) = 866 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.170 ms/op
     p(99.9000) =     12.190 ms/op
     p(99.9900) =     12.481 ms/op
     p(99.9990) =     12.550 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.089 ms/op
Iteration   1: 1.966 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 12.196 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16295
  mean =      1.966 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 204 
    [ 1.250,  2.500) = 14838 
    [ 2.500,  3.750) = 1023 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     12.196 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 4.419 ±(99.9%) 0.127 ms/op
Iteration   1: 3.196 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.854 ms/op
                 listUser·p0.999:  23.199 ms/op
                 listUser·p0.9999: 24.084 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10012
  mean =      3.196 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1968 
    [ 2.500,  5.000) = 7702 
    [ 5.000,  7.500) = 224 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.854 ms/op
     p(99.9000) =     23.199 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.270          ops/ms
ClientSimple.existUser                       thrpt         12.343          ops/ms
ClientSimple.getUser                         thrpt         13.252          ops/ms
ClientSimple.listUser                        thrpt          8.430          ops/ms
ClientSimple.createUser                       avgt          2.169           ms/op
ClientSimple.existUser                        avgt          1.906           ms/op
ClientSimple.getUser                          avgt          1.862           ms/op
ClientSimple.listUser                         avgt          3.481           ms/op
ClientSimple.createUser                     sample  14797   2.161 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.929           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.901           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.043           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.308           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.323           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.890           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.906           ms/op
ClientSimple.existUser                      sample  16999   1.880 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.410           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.170           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.190           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.481           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.550           ms/op
ClientSimple.getUser                        sample  16295   1.966 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.578           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.850           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.911           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.196           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.485           ms/op
ClientSimple.listUser                       sample  10012   3.196 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.876           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.879           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.014           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.854           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.199           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.084           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.084           ms/op

Benchmark result is saved to 1720505611823.json
