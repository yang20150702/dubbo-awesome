# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.350 ops/ms
Iteration   1: 5.822 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.822 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.989 ops/ms
Iteration   1: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.604 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ops/ms
Iteration   1: 8.651 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.651 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.841 ops/ms
Iteration   1: 3.488 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.488 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.910 ±(99.9%) 0.072 ms/op
Iteration   1: 3.040 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.647 ±(99.9%) 0.042 ms/op
Iteration   1: 1.834 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.058 ±(99.9%) 0.045 ms/op
Iteration   1: 3.266 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.137 ±(99.9%) 0.396 ms/op
Iteration   1: 9.049 ±(99.9%) 0.098 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.049 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.755 ±(99.9%) 0.098 ms/op
Iteration   1: 3.308 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   12.834 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9664
  mean =      3.308 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1940 
    [ 2.500,  3.750) = 5829 
    [ 3.750,  5.000) = 1476 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =     12.834 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ±(99.9%) 0.265 ms/op
Iteration   1: 1.850 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   1.647 ms/op
                 existUser·p0.90:   2.580 ms/op
                 existUser·p0.95:   2.793 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  15.876 ms/op
                 existUser·p0.9999: 16.573 ms/op
                 existUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17295
  mean =      1.850 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1138 
    [ 1.250,  2.500) = 13997 
    [ 2.500,  3.750) = 2072 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.318 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     16.573 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ±(99.9%) 0.150 ms/op
Iteration   1: 3.071 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  8.402 ms/op
                 getUser·p0.9999: 8.995 ms/op
                 getUser·p1.00:   8.995 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10399
  mean =      3.071 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 41 
    [1.500, 2.000) = 195 
    [2.000, 2.500) = 2013 
    [2.500, 3.000) = 2874 
    [3.000, 3.500) = 2719 
    [3.500, 4.000) = 1954 
    [4.000, 4.500) = 377 
    [4.500, 5.000) = 90 
    [5.000, 5.500) = 37 
    [5.500, 6.000) = 11 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =      8.402 ms/op
     p(99.9900) =      8.995 ms/op
     p(99.9990) =      8.995 ms/op
     p(99.9999) =      8.995 ms/op
    p(100.0000) =      8.995 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.660 ±(99.9%) 0.402 ms/op
Iteration   1: 7.929 ±(99.9%) 0.194 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   7.352 ms/op
                 listUser·p0.90:   10.002 ms/op
                 listUser·p0.95:   11.272 ms/op
                 listUser·p0.99:   19.990 ms/op
                 listUser·p0.999:  46.331 ms/op
                 listUser·p0.9999: 55.575 ms/op
                 listUser·p1.00:   55.575 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4044
  mean =      7.929 ±(99.9%) 0.194 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 117 
    [ 5.000, 10.000) = 3523 
    [10.000, 15.000) = 322 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      7.352 ms/op
     p(90.0000) =     10.002 ms/op
     p(95.0000) =     11.272 ms/op
     p(99.0000) =     19.990 ms/op
     p(99.9000) =     46.331 ms/op
     p(99.9900) =     55.575 ms/op
     p(99.9990) =     55.575 ms/op
     p(99.9999) =     55.575 ms/op
    p(100.0000) =     55.575 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.822          ops/ms
Client.existUser                       thrpt         12.604          ops/ms
Client.getUser                         thrpt          8.651          ops/ms
Client.listUser                        thrpt          3.488          ops/ms
Client.createUser                       avgt          3.040           ms/op
Client.existUser                        avgt          1.834           ms/op
Client.getUser                          avgt          3.266           ms/op
Client.listUser                         avgt          9.049           ms/op
Client.createUser                     sample   9664   3.308 ± 0.054   ms/op
Client.createUser:createUser·p0.00    sample          1.384           ms/op
Client.createUser:createUser·p0.50    sample          2.990           ms/op
Client.createUser:createUser·p0.90    sample          4.121           ms/op
Client.createUser:createUser·p0.95    sample          4.817           ms/op
Client.createUser:createUser·p0.99    sample         12.834           ms/op
Client.createUser:createUser·p0.999   sample         17.203           ms/op
Client.createUser:createUser·p0.9999  sample         19.562           ms/op
Client.createUser:createUser·p1.00    sample         19.562           ms/op
Client.existUser                      sample  17295   1.850 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.654           ms/op
Client.existUser:existUser·p0.50      sample          1.647           ms/op
Client.existUser:existUser·p0.90      sample          2.580           ms/op
Client.existUser:existUser·p0.95      sample          2.793           ms/op
Client.existUser:existUser·p0.99      sample          3.318           ms/op
Client.existUser:existUser·p0.999     sample         15.876           ms/op
Client.existUser:existUser·p0.9999    sample         16.573           ms/op
Client.existUser:existUser·p1.00      sample         16.597           ms/op
Client.getUser                        sample  10399   3.071 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.881           ms/op
Client.getUser:getUser·p0.50          sample          3.019           ms/op
Client.getUser:getUser·p0.90          sample          3.854           ms/op
Client.getUser:getUser·p0.95          sample          4.035           ms/op
Client.getUser:getUser·p0.99          sample          5.358           ms/op
Client.getUser:getUser·p0.999         sample          8.402           ms/op
Client.getUser:getUser·p0.9999        sample          8.995           ms/op
Client.getUser:getUser·p1.00          sample          8.995           ms/op
Client.listUser                       sample   4044   7.929 ± 0.194   ms/op
Client.listUser:listUser·p0.00        sample          1.606           ms/op
Client.listUser:listUser·p0.50        sample          7.352           ms/op
Client.listUser:listUser·p0.90        sample         10.002           ms/op
Client.listUser:listUser·p0.95        sample         11.272           ms/op
Client.listUser:listUser·p0.99        sample         19.990           ms/op
Client.listUser:listUser·p0.999       sample         46.331           ms/op
Client.listUser:listUser·p0.9999      sample         55.575           ms/op
Client.listUser:listUser·p1.00        sample         55.575           ms/op
