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
# Warmup Iteration   1: 2.475 ops/ms
Iteration   1: 6.389 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.389 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.409 ops/ms
Iteration   1: 12.944 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.944 ops/ms


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
# Warmup Iteration   1: 4.694 ops/ms
Iteration   1: 10.163 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.163 ops/ms


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
# Warmup Iteration   1: 2.265 ops/ms
Iteration   1: 4.079 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.079 ops/ms


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
# Warmup Iteration   1: 5.352 ±(99.9%) 0.077 ms/op
Iteration   1: 3.427 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.427 ms/op


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
# Warmup Iteration   1: 3.006 ±(99.9%) 0.038 ms/op
Iteration   1: 2.046 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.046 ms/op


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
# Warmup Iteration   1: 5.029 ±(99.9%) 0.063 ms/op
Iteration   1: 3.160 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.160 ms/op


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
# Warmup Iteration   1: 11.745 ±(99.9%) 0.182 ms/op
Iteration   1: 9.053 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.053 ms/op


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
# Warmup Iteration   1: 4.978 ±(99.9%) 0.102 ms/op
Iteration   1: 3.123 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   2.896 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   8.260 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 14.384 ms/op
                 createUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10237
  mean =      3.123 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1671 
    [ 2.500,  3.750) = 7260 
    [ 3.750,  5.000) = 1032 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      8.260 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     14.384 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.085 ms/op
Iteration   1: 1.935 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   1.874 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   3.301 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 17.640 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16568
  mean =      1.935 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 739 
    [ 1.250,  2.500) = 14514 
    [ 2.500,  3.750) = 1213 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.301 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     17.640 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.432 ±(99.9%) 0.101 ms/op
Iteration   1: 3.276 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   7.663 ms/op
                 getUser·p0.999:  10.551 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9757
  mean =      3.276 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1050 
    [ 2.500,  3.750) = 7259 
    [ 3.750,  5.000) = 1187 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.663 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 10.864 ±(99.9%) 0.338 ms/op
Iteration   1: 8.575 ±(99.9%) 0.133 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   8.200 ms/op
                 listUser·p0.90:   11.354 ms/op
                 listUser·p0.95:   12.698 ms/op
                 listUser·p0.99:   16.055 ms/op
                 listUser·p0.999:  24.763 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3753
  mean =      8.575 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 83 
    [ 5.000,  7.500) = 1168 
    [ 7.500, 10.000) = 1751 
    [10.000, 12.500) = 531 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.662 ms/op
     p(50.0000) =      8.200 ms/op
     p(90.0000) =     11.354 ms/op
     p(95.0000) =     12.698 ms/op
     p(99.0000) =     16.055 ms/op
     p(99.9000) =     24.763 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.389          ops/ms
Client.existUser                       thrpt         12.944          ops/ms
Client.getUser                         thrpt         10.163          ops/ms
Client.listUser                        thrpt          4.079          ops/ms
Client.createUser                       avgt          3.427           ms/op
Client.existUser                        avgt          2.046           ms/op
Client.getUser                          avgt          3.160           ms/op
Client.listUser                         avgt          9.053           ms/op
Client.createUser                     sample  10237   3.123 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          0.779           ms/op
Client.createUser:createUser·p0.50    sample          2.896           ms/op
Client.createUser:createUser·p0.90    sample          3.994           ms/op
Client.createUser:createUser·p0.95    sample          4.547           ms/op
Client.createUser:createUser·p0.99    sample          8.260           ms/op
Client.createUser:createUser·p0.999   sample         12.517           ms/op
Client.createUser:createUser·p0.9999  sample         14.384           ms/op
Client.createUser:createUser·p1.00    sample         14.385           ms/op
Client.existUser                      sample  16568   1.935 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.566           ms/op
Client.existUser:existUser·p0.50      sample          1.874           ms/op
Client.existUser:existUser·p0.90      sample          2.429           ms/op
Client.existUser:existUser·p0.95      sample          2.626           ms/op
Client.existUser:existUser·p0.99      sample          3.301           ms/op
Client.existUser:existUser·p0.999     sample         17.367           ms/op
Client.existUser:existUser·p0.9999    sample         17.640           ms/op
Client.existUser:existUser·p1.00      sample         17.662           ms/op
Client.getUser                        sample   9757   3.276 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          1.165           ms/op
Client.getUser:getUser·p0.50          sample          3.187           ms/op
Client.getUser:getUser·p0.90          sample          3.912           ms/op
Client.getUser:getUser·p0.95          sample          4.334           ms/op
Client.getUser:getUser·p0.99          sample          7.663           ms/op
Client.getUser:getUser·p0.999         sample         10.551           ms/op
Client.getUser:getUser·p0.9999        sample         13.763           ms/op
Client.getUser:getUser·p1.00          sample         13.763           ms/op
Client.listUser                       sample   3753   8.575 ± 0.133   ms/op
Client.listUser:listUser·p0.00        sample          2.662           ms/op
Client.listUser:listUser·p0.50        sample          8.200           ms/op
Client.listUser:listUser·p0.90        sample         11.354           ms/op
Client.listUser:listUser·p0.95        sample         12.698           ms/op
Client.listUser:listUser·p0.99        sample         16.055           ms/op
Client.listUser:listUser·p0.999       sample         24.763           ms/op
Client.listUser:listUser·p0.9999      sample         25.723           ms/op
Client.listUser:listUser·p1.00        sample         25.723           ms/op
