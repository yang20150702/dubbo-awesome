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
# Warmup Iteration   1: 1.600 ops/ms
Iteration   1: 3.753 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.753 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ops/ms
Iteration   1: 10.082 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.082 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.275 ops/ms
Iteration   1: 6.640 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.640 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.120 ops/ms
Iteration   1: 1.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.680 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 11.181 ±(99.9%) 0.222 ms/op
Iteration   1: 5.693 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.693 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.226 ±(99.9%) 0.107 ms/op
Iteration   1: 2.738 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.738 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.100 ±(99.9%) 0.106 ms/op
Iteration   1: 3.811 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.811 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 22.864 ±(99.9%) 0.545 ms/op
Iteration   1: 15.247 ±(99.9%) 0.147 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.247 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.026 ±(99.9%) 0.277 ms/op
Iteration   1: 3.901 ±(99.9%) 0.118 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   2.773 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   8.829 ms/op
                 createUser·p0.99:   18.645 ms/op
                 createUser·p0.999:  42.936 ms/op
                 createUser·p0.9999: 44.171 ms/op
                 createUser·p1.00:   44.171 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8421
  mean =      3.901 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7219 
    [ 5.000, 10.000) = 965 
    [10.000, 15.000) = 141 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      8.829 ms/op
     p(99.0000) =     18.645 ms/op
     p(99.9000) =     42.936 ms/op
     p(99.9900) =     44.171 ms/op
     p(99.9990) =     44.171 ms/op
     p(99.9999) =     44.171 ms/op
    p(100.0000) =     44.171 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.000 ±(99.9%) 0.265 ms/op
Iteration   1: 2.486 ±(99.9%) 0.052 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.208 ms/op
                 existUser·p0.90:   2.875 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   11.352 ms/op
                 existUser·p0.999:  26.154 ms/op
                 existUser·p0.9999: 28.561 ms/op
                 existUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 12842
  mean =      2.486 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10615 
    [ 2.500,  5.000) = 1872 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.208 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =     11.352 ms/op
     p(99.9000) =     26.154 ms/op
     p(99.9900) =     28.561 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 6.829 ±(99.9%) 0.275 ms/op
Iteration   1: 3.228 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.671 ms/op
                 getUser·p0.99:   12.197 ms/op
                 getUser·p0.999:  17.600 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9894
  mean =      3.228 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 836 
    [ 2.500,  3.750) = 8128 
    [ 3.750,  5.000) = 525 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.671 ms/op
     p(99.0000) =     12.197 ms/op
     p(99.9000) =     17.600 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 23.887 ±(99.9%) 1.029 ms/op
Iteration   1: 14.769 ±(99.9%) 0.295 ms/op
                 listUser·p0.00:   4.092 ms/op
                 listUser·p0.50:   14.426 ms/op
                 listUser·p0.90:   19.861 ms/op
                 listUser·p0.95:   22.087 ms/op
                 listUser·p0.99:   26.451 ms/op
                 listUser·p0.999:  32.310 ms/op
                 listUser·p0.9999: 35.455 ms/op
                 listUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2178
  mean =     14.769 ±(99.9%) 0.295 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 3 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 557 
    [15.000, 17.500) = 466 
    [17.500, 20.000) = 283 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      4.092 ms/op
     p(50.0000) =     14.426 ms/op
     p(90.0000) =     19.861 ms/op
     p(95.0000) =     22.087 ms/op
     p(99.0000) =     26.451 ms/op
     p(99.9000) =     32.310 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.753          ops/ms
Client.existUser                       thrpt         10.082          ops/ms
Client.getUser                         thrpt          6.640          ops/ms
Client.listUser                        thrpt          1.680          ops/ms
Client.createUser                       avgt          5.693           ms/op
Client.existUser                        avgt          2.738           ms/op
Client.getUser                          avgt          3.811           ms/op
Client.listUser                         avgt         15.247           ms/op
Client.createUser                     sample   8421   3.901 ± 0.118   ms/op
Client.createUser:createUser·p0.00    sample          1.231           ms/op
Client.createUser:createUser·p0.50    sample          2.773           ms/op
Client.createUser:createUser·p0.90    sample          5.677           ms/op
Client.createUser:createUser·p0.95    sample          8.829           ms/op
Client.createUser:createUser·p0.99    sample         18.645           ms/op
Client.createUser:createUser·p0.999   sample         42.936           ms/op
Client.createUser:createUser·p0.9999  sample         44.171           ms/op
Client.createUser:createUser·p1.00    sample         44.171           ms/op
Client.existUser                      sample  12842   2.486 ± 0.052   ms/op
Client.existUser:existUser·p0.00      sample          0.862           ms/op
Client.existUser:existUser·p0.50      sample          2.208           ms/op
Client.existUser:existUser·p0.90      sample          2.875           ms/op
Client.existUser:existUser·p0.95      sample          3.899           ms/op
Client.existUser:existUser·p0.99      sample         11.352           ms/op
Client.existUser:existUser·p0.999     sample         26.154           ms/op
Client.existUser:existUser·p0.9999    sample         28.561           ms/op
Client.existUser:existUser·p1.00      sample         28.803           ms/op
Client.getUser                        sample   9894   3.228 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample          0.745           ms/op
Client.getUser:getUser·p0.50          sample          2.945           ms/op
Client.getUser:getUser·p0.90          sample          3.703           ms/op
Client.getUser:getUser·p0.95          sample          4.671           ms/op
Client.getUser:getUser·p0.99          sample         12.197           ms/op
Client.getUser:getUser·p0.999         sample         17.600           ms/op
Client.getUser:getUser·p0.9999        sample         19.923           ms/op
Client.getUser:getUser·p1.00          sample         19.923           ms/op
Client.listUser                       sample   2178  14.769 ± 0.295   ms/op
Client.listUser:listUser·p0.00        sample          4.092           ms/op
Client.listUser:listUser·p0.50        sample         14.426           ms/op
Client.listUser:listUser·p0.90        sample         19.861           ms/op
Client.listUser:listUser·p0.95        sample         22.087           ms/op
Client.listUser:listUser·p0.99        sample         26.451           ms/op
Client.listUser:listUser·p0.999       sample         32.310           ms/op
Client.listUser:listUser·p0.9999      sample         35.455           ms/op
Client.listUser:listUser·p1.00        sample         35.455           ms/op
