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
# Warmup Iteration   1: 1.748 ops/ms
Iteration   1: 5.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.982 ops/ms


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
# Warmup Iteration   1: 5.079 ops/ms
Iteration   1: 10.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.877 ops/ms


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
# Warmup Iteration   1: 5.010 ops/ms
Iteration   1: 11.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.408 ops/ms


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
# Warmup Iteration   1: 3.784 ops/ms
Iteration   1: 7.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.709 ops/ms


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.069 ms/op
Iteration   1: 2.352 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.352 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.072 ms/op
Iteration   1: 2.045 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.045 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.065 ms/op
Iteration   1: 1.906 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.393 ±(99.9%) 0.093 ms/op
Iteration   1: 3.690 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.690 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.107 ms/op
Iteration   1: 2.453 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.408 ms/op
                 createUser·p0.50:   2.302 ms/op
                 createUser·p0.90:   2.867 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   9.343 ms/op
                 createUser·p0.999:  15.647 ms/op
                 createUser·p0.9999: 20.656 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13073
  mean =      2.453 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9017 
    [ 2.500,  5.000) = 3786 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      2.302 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      9.343 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     20.656 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 3.049 ±(99.9%) 0.079 ms/op
Iteration   1: 1.955 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   1.929 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.150 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 13.225 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16350
  mean =      1.955 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 540 
    [ 1.250,  2.500) = 14633 
    [ 2.500,  3.750) = 1051 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.150 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     13.225 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.089 ms/op
Iteration   1: 1.954 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   1.874 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   3.117 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 12.147 ms/op
                 getUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16362
  mean =      1.954 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 15169 
    [ 2.500,  3.750) = 977 
    [ 3.750,  5.000) = 5 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.117 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     12.147 ms/op
     p(99.9990) =     12.157 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.123 ms/op
Iteration   1: 3.872 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  12.222 ms/op
                 listUser·p0.9999: 12.501 ms/op
                 listUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8262
  mean =      3.872 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 275 
    [ 2.500,  3.750) = 3847 
    [ 3.750,  5.000) = 3467 
    [ 5.000,  6.250) = 546 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     12.501 ms/op
     p(99.9990) =     12.501 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.982          ops/ms
ClientSimple.existUser                       thrpt         10.877          ops/ms
ClientSimple.getUser                         thrpt         11.408          ops/ms
ClientSimple.listUser                        thrpt          7.709          ops/ms
ClientSimple.createUser                       avgt          2.352           ms/op
ClientSimple.existUser                        avgt          2.045           ms/op
ClientSimple.getUser                          avgt          1.906           ms/op
ClientSimple.listUser                         avgt          3.690           ms/op
ClientSimple.createUser                     sample  13073   2.453 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.408           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.302           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.343           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.647           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.656           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.677           ms/op
ClientSimple.existUser                      sample  16350   1.955 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.744           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.929           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.150           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.747           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.225           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.287           ms/op
ClientSimple.getUser                        sample  16362   1.954 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.670           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.874           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.117           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.813           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.147           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.157           ms/op
ClientSimple.listUser                       sample   8262   3.872 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.939           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.907           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.186           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.545           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.222           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.501           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.501           ms/op

Benchmark result is saved to 1721110430658.json
