# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.268 ops/ms
Iteration   1: 4.408 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.408 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 3.657 ops/ms
Iteration   1: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.213 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.807 ops/ms
Iteration   1: 5.584 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.584 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.124 ops/ms
Iteration   1: 1.736 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.736 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 9.950 ±(99.9%) 0.163 ms/op
Iteration   1: 4.812 ±(99.9%) 0.107 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.812 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 5.700 ±(99.9%) 0.079 ms/op
Iteration   1: 2.533 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.889 ±(99.9%) 0.145 ms/op
Iteration   1: 4.395 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.395 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 27.694 ±(99.9%) 0.622 ms/op
Iteration   1: 15.743 ±(99.9%) 0.116 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.743 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.438 ±(99.9%) 0.239 ms/op
Iteration   1: 3.987 ±(99.9%) 0.067 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   7.878 ms/op
                 createUser·p0.99:   13.107 ms/op
                 createUser·p0.999:  15.081 ms/op
                 createUser·p0.9999: 16.318 ms/op
                 createUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8026
  mean =      3.987 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 307 
    [ 2.500,  3.750) = 4951 
    [ 3.750,  5.000) = 1639 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 267 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      7.878 ms/op
     p(99.0000) =     13.107 ms/op
     p(99.9000) =     15.081 ms/op
     p(99.9900) =     16.318 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.184 ±(99.9%) 0.219 ms/op
Iteration   1: 2.610 ±(99.9%) 0.064 ms/op
                 existUser·p0.00:   0.451 ms/op
                 existUser·p0.50:   2.046 ms/op
                 existUser·p0.90:   3.960 ms/op
                 existUser·p0.95:   6.856 ms/op
                 existUser·p0.99:   11.069 ms/op
                 existUser·p0.999:  23.189 ms/op
                 existUser·p0.9999: 24.773 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 12340
  mean =      2.610 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9485 
    [ 2.500,  5.000) = 1869 
    [ 5.000,  7.500) = 465 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      3.960 ms/op
     p(95.0000) =      6.856 ms/op
     p(99.0000) =     11.069 ms/op
     p(99.9000) =     23.189 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 8.864 ±(99.9%) 0.274 ms/op
Iteration   1: 4.363 ±(99.9%) 0.339 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   7.283 ms/op
                 getUser·p0.99:   27.013 ms/op
                 getUser·p0.999:  148.015 ms/op
                 getUser·p0.9999: 175.636 ms/op
                 getUser·p1.00:   175.636 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7591
  mean =      4.363 ±(99.9%) 0.339 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 7461 
    [ 12.500,  25.000) = 50 
    [ 25.000,  37.500) = 39 
    [ 37.500,  50.000) = 4 
    [ 50.000,  62.500) = 2 
    [ 62.500,  75.000) = 1 
    [ 75.000,  87.500) = 4 
    [ 87.500, 100.000) = 2 
    [100.000, 112.500) = 1 
    [112.500, 125.000) = 7 
    [125.000, 137.500) = 4 
    [137.500, 150.000) = 10 
    [150.000, 162.500) = 3 
    [162.500, 175.000) = 2 
    [175.000, 187.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      7.283 ms/op
     p(99.0000) =     27.013 ms/op
     p(99.9000) =    148.015 ms/op
     p(99.9900) =    175.636 ms/op
     p(99.9990) =    175.636 ms/op
     p(99.9999) =    175.636 ms/op
    p(100.0000) =    175.636 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 22.988 ±(99.9%) 0.795 ms/op
Iteration   1: 16.169 ±(99.9%) 0.417 ms/op
                 listUser·p0.00:   4.059 ms/op
                 listUser·p0.50:   14.942 ms/op
                 listUser·p0.90:   23.757 ms/op
                 listUser·p0.95:   27.361 ms/op
                 listUser·p0.99:   34.157 ms/op
                 listUser·p0.999:  43.445 ms/op
                 listUser·p0.9999: 44.106 ms/op
                 listUser·p1.00:   44.106 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2039
  mean =     16.169 ±(99.9%) 0.417 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2 
    [ 5.000, 10.000) = 202 
    [10.000, 15.000) = 825 
    [15.000, 20.000) = 570 
    [20.000, 25.000) = 294 
    [25.000, 30.000) = 84 
    [30.000, 35.000) = 48 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      4.059 ms/op
     p(50.0000) =     14.942 ms/op
     p(90.0000) =     23.757 ms/op
     p(95.0000) =     27.361 ms/op
     p(99.0000) =     34.157 ms/op
     p(99.9000) =     43.445 ms/op
     p(99.9900) =     44.106 ms/op
     p(99.9990) =     44.106 ms/op
     p(99.9999) =     44.106 ms/op
    p(100.0000) =     44.106 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           4.408          ops/ms
Client.existUser                       thrpt          10.213          ops/ms
Client.getUser                         thrpt           5.584          ops/ms
Client.listUser                        thrpt           1.736          ops/ms
Client.createUser                       avgt           4.812           ms/op
Client.existUser                        avgt           2.533           ms/op
Client.getUser                          avgt           4.395           ms/op
Client.listUser                         avgt          15.743           ms/op
Client.createUser                     sample   8026    3.987 ± 0.067   ms/op
Client.createUser:createUser·p0.00    sample           1.458           ms/op
Client.createUser:createUser·p0.50    sample           3.445           ms/op
Client.createUser:createUser·p0.90    sample           5.956           ms/op
Client.createUser:createUser·p0.95    sample           7.878           ms/op
Client.createUser:createUser·p0.99    sample          13.107           ms/op
Client.createUser:createUser·p0.999   sample          15.081           ms/op
Client.createUser:createUser·p0.9999  sample          16.318           ms/op
Client.createUser:createUser·p1.00    sample          16.318           ms/op
Client.existUser                      sample  12340    2.610 ± 0.064   ms/op
Client.existUser:existUser·p0.00      sample           0.451           ms/op
Client.existUser:existUser·p0.50      sample           2.046           ms/op
Client.existUser:existUser·p0.90      sample           3.960           ms/op
Client.existUser:existUser·p0.95      sample           6.856           ms/op
Client.existUser:existUser·p0.99      sample          11.069           ms/op
Client.existUser:existUser·p0.999     sample          23.189           ms/op
Client.existUser:existUser·p0.9999    sample          24.773           ms/op
Client.existUser:existUser·p1.00      sample          24.904           ms/op
Client.getUser                        sample   7591    4.363 ± 0.339   ms/op
Client.getUser:getUser·p0.00          sample           1.015           ms/op
Client.getUser:getUser·p0.50          sample           3.318           ms/op
Client.getUser:getUser·p0.90          sample           4.792           ms/op
Client.getUser:getUser·p0.95          sample           7.283           ms/op
Client.getUser:getUser·p0.99          sample          27.013           ms/op
Client.getUser:getUser·p0.999         sample         148.015           ms/op
Client.getUser:getUser·p0.9999        sample         175.636           ms/op
Client.getUser:getUser·p1.00          sample         175.636           ms/op
Client.listUser                       sample   2039   16.169 ± 0.417   ms/op
Client.listUser:listUser·p0.00        sample           4.059           ms/op
Client.listUser:listUser·p0.50        sample          14.942           ms/op
Client.listUser:listUser·p0.90        sample          23.757           ms/op
Client.listUser:listUser·p0.95        sample          27.361           ms/op
Client.listUser:listUser·p0.99        sample          34.157           ms/op
Client.listUser:listUser·p0.999       sample          43.445           ms/op
Client.listUser:listUser·p0.9999      sample          44.106           ms/op
Client.listUser:listUser·p1.00        sample          44.106           ms/op
