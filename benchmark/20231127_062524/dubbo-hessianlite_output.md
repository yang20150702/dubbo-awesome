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
# Warmup Iteration   1: 2.434 ops/ms
Iteration   1: 5.870 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.870 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.386 ops/ms
Iteration   1: 13.277 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.277 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.700 ops/ms
Iteration   1: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.592 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.968 ops/ms
Iteration   1: 3.745 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.745 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.260 ±(99.9%) 0.066 ms/op
Iteration   1: 3.060 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.060 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.984 ±(99.9%) 0.027 ms/op
Iteration   1: 1.846 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.846 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.638 ±(99.9%) 0.053 ms/op
Iteration   1: 2.829 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.829 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.171 ±(99.9%) 0.132 ms/op
Iteration   1: 7.266 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.266 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.556 ±(99.9%) 0.088 ms/op
Iteration   1: 2.850 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   6.962 ms/op
                 createUser·p0.999:  27.886 ms/op
                 createUser·p0.9999: 28.927 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11216
  mean =      2.850 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3149 
    [ 2.500,  5.000) = 7872 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      6.962 ms/op
     p(99.9000) =     27.886 ms/op
     p(99.9900) =     28.927 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.981 ±(99.9%) 0.048 ms/op
Iteration   1: 1.858 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   3.161 ms/op
                 existUser·p0.999:  12.772 ms/op
                 existUser·p0.9999: 12.973 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17225
  mean =      1.858 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 439 
    [ 1.250,  2.500) = 15266 
    [ 2.500,  3.750) = 1432 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      3.161 ms/op
     p(99.9000) =     12.772 ms/op
     p(99.9900) =     12.973 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.197 ±(99.9%) 0.094 ms/op
Iteration   1: 2.965 ±(99.9%) 0.102 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   6.665 ms/op
                 getUser·p0.999:  58.421 ms/op
                 getUser·p0.9999: 61.979 ms/op
                 getUser·p1.00:   62.194 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10780
  mean =      2.965 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10632 
    [ 5.000, 10.000) = 52 
    [10.000, 15.000) = 10 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 31 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      6.665 ms/op
     p(99.9000) =     58.421 ms/op
     p(99.9900) =     61.979 ms/op
     p(99.9990) =     62.194 ms/op
     p(99.9999) =     62.194 ms/op
    p(100.0000) =     62.194 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 10.647 ±(99.9%) 0.306 ms/op
Iteration   1: 8.590 ±(99.9%) 0.132 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   8.294 ms/op
                 listUser·p0.90:   11.513 ms/op
                 listUser·p0.95:   12.845 ms/op
                 listUser·p0.99:   18.611 ms/op
                 listUser·p0.999:  21.309 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3712
  mean =      8.590 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 136 
    [ 5.000,  7.500) = 1128 
    [ 7.500, 10.000) = 1622 
    [10.000, 12.500) = 596 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.679 ms/op
     p(50.0000) =      8.294 ms/op
     p(90.0000) =     11.513 ms/op
     p(95.0000) =     12.845 ms/op
     p(99.0000) =     18.611 ms/op
     p(99.9000) =     21.309 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.870          ops/ms
Client.existUser                       thrpt         13.277          ops/ms
Client.getUser                         thrpt          9.592          ops/ms
Client.listUser                        thrpt          3.745          ops/ms
Client.createUser                       avgt          3.060           ms/op
Client.existUser                        avgt          1.846           ms/op
Client.getUser                          avgt          2.829           ms/op
Client.listUser                         avgt          7.266           ms/op
Client.createUser                     sample  11216   2.850 ± 0.049   ms/op
Client.createUser:createUser·p0.00    sample          1.096           ms/op
Client.createUser:createUser·p0.50    sample          2.666           ms/op
Client.createUser:createUser·p0.90    sample          3.150           ms/op
Client.createUser:createUser·p0.95    sample          3.596           ms/op
Client.createUser:createUser·p0.99    sample          6.962           ms/op
Client.createUser:createUser·p0.999   sample         27.886           ms/op
Client.createUser:createUser·p0.9999  sample         28.927           ms/op
Client.createUser:createUser·p1.00    sample         28.967           ms/op
Client.existUser                      sample  17225   1.858 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.769           ms/op
Client.existUser:existUser·p0.50      sample          1.761           ms/op
Client.existUser:existUser·p0.90      sample          2.470           ms/op
Client.existUser:existUser·p0.95      sample          2.634           ms/op
Client.existUser:existUser·p0.99      sample          3.161           ms/op
Client.existUser:existUser·p0.999     sample         12.772           ms/op
Client.existUser:existUser·p0.9999    sample         12.973           ms/op
Client.existUser:existUser·p1.00      sample         13.009           ms/op
Client.getUser                        sample  10780   2.965 ± 0.102   ms/op
Client.getUser:getUser·p0.00          sample          0.584           ms/op
Client.getUser:getUser·p0.50          sample          2.621           ms/op
Client.getUser:getUser·p0.90          sample          3.572           ms/op
Client.getUser:getUser·p0.95          sample          3.817           ms/op
Client.getUser:getUser·p0.99          sample          6.665           ms/op
Client.getUser:getUser·p0.999         sample         58.421           ms/op
Client.getUser:getUser·p0.9999        sample         61.979           ms/op
Client.getUser:getUser·p1.00          sample         62.194           ms/op
Client.listUser                       sample   3712   8.590 ± 0.132   ms/op
Client.listUser:listUser·p0.00        sample          2.679           ms/op
Client.listUser:listUser·p0.50        sample          8.294           ms/op
Client.listUser:listUser·p0.90        sample         11.513           ms/op
Client.listUser:listUser·p0.95        sample         12.845           ms/op
Client.listUser:listUser·p0.99        sample         18.611           ms/op
Client.listUser:listUser·p0.999       sample         21.309           ms/op
Client.listUser:listUser·p0.9999      sample         23.200           ms/op
Client.listUser:listUser·p1.00        sample         23.200           ms/op
