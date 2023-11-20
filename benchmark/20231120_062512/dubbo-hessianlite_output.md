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
# Warmup Iteration   1: 2.480 ops/ms
Iteration   1: 5.706 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.706 ops/ms


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
# Warmup Iteration   1: 6.920 ops/ms
Iteration   1: 13.623 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.623 ops/ms


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
# Warmup Iteration   1: 4.621 ops/ms
Iteration   1: 9.152 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.152 ops/ms


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
# Warmup Iteration   1: 2.258 ops/ms
Iteration   1: 4.127 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.127 ops/ms


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.065 ms/op
Iteration   1: 2.771 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.771 ms/op


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
# Warmup Iteration   1: 2.962 ±(99.9%) 0.031 ms/op
Iteration   1: 1.893 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.058 ms/op
Iteration   1: 3.094 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.094 ms/op


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
# Warmup Iteration   1: 10.962 ±(99.9%) 0.194 ms/op
Iteration   1: 8.288 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.288 ms/op


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
# Warmup Iteration   1: 4.844 ±(99.9%) 0.089 ms/op
Iteration   1: 3.103 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   2.826 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   11.795 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10305
  mean =      3.103 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2426 
    [ 2.500,  3.750) = 6932 
    [ 3.750,  5.000) = 581 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =     11.795 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 2.860 ±(99.9%) 0.061 ms/op
Iteration   1: 1.798 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   3.133 ms/op
                 existUser·p0.999:  16.464 ms/op
                 existUser·p0.9999: 17.825 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18054
  mean =      1.798 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 812 
    [ 1.250,  2.500) = 16545 
    [ 2.500,  3.750) = 578 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.133 ms/op
     p(99.9000) =     16.464 ms/op
     p(99.9900) =     17.825 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.080 ms/op
Iteration   1: 2.735 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.310 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   6.102 ms/op
                 getUser·p0.999:  24.740 ms/op
                 getUser·p0.9999: 24.969 ms/op
                 getUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11762
  mean =      2.735 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5952 
    [ 2.500,  5.000) = 5639 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      6.102 ms/op
     p(99.9000) =     24.740 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 11.733 ±(99.9%) 0.390 ms/op
Iteration   1: 8.899 ±(99.9%) 0.130 ms/op
                 listUser·p0.00:   3.715 ms/op
                 listUser·p0.50:   8.520 ms/op
                 listUser·p0.90:   11.867 ms/op
                 listUser·p0.95:   12.763 ms/op
                 listUser·p0.99:   18.129 ms/op
                 listUser·p0.999:  20.102 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3586
  mean =      8.899 ±(99.9%) 0.130 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 18 
    [ 5.000,  7.500) = 1129 
    [ 7.500, 10.000) = 1470 
    [10.000, 12.500) = 745 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.715 ms/op
     p(50.0000) =      8.520 ms/op
     p(90.0000) =     11.867 ms/op
     p(95.0000) =     12.763 ms/op
     p(99.0000) =     18.129 ms/op
     p(99.9000) =     20.102 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.706          ops/ms
Client.existUser                       thrpt         13.623          ops/ms
Client.getUser                         thrpt          9.152          ops/ms
Client.listUser                        thrpt          4.127          ops/ms
Client.createUser                       avgt          2.771           ms/op
Client.existUser                        avgt          1.893           ms/op
Client.getUser                          avgt          3.094           ms/op
Client.listUser                         avgt          8.288           ms/op
Client.createUser                     sample  10305   3.103 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          0.975           ms/op
Client.createUser:createUser·p0.50    sample          2.826           ms/op
Client.createUser:createUser·p0.90    sample          3.690           ms/op
Client.createUser:createUser·p0.95    sample          4.284           ms/op
Client.createUser:createUser·p0.99    sample         11.795           ms/op
Client.createUser:createUser·p0.999   sample         17.957           ms/op
Client.createUser:createUser·p0.9999  sample         18.055           ms/op
Client.createUser:createUser·p1.00    sample         18.055           ms/op
Client.existUser                      sample  18054   1.798 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.609           ms/op
Client.existUser:existUser·p0.50      sample          1.698           ms/op
Client.existUser:existUser·p0.90      sample          2.261           ms/op
Client.existUser:existUser·p0.95      sample          2.437           ms/op
Client.existUser:existUser·p0.99      sample          3.133           ms/op
Client.existUser:existUser·p0.999     sample         16.464           ms/op
Client.existUser:existUser·p0.9999    sample         17.825           ms/op
Client.existUser:existUser·p1.00      sample         17.957           ms/op
Client.getUser                        sample  11762   2.735 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample          1.007           ms/op
Client.getUser:getUser·p0.50          sample          2.494           ms/op
Client.getUser:getUser·p0.90          sample          3.310           ms/op
Client.getUser:getUser·p0.95          sample          3.666           ms/op
Client.getUser:getUser·p0.99          sample          6.102           ms/op
Client.getUser:getUser·p0.999         sample         24.740           ms/op
Client.getUser:getUser·p0.9999        sample         24.969           ms/op
Client.getUser:getUser·p1.00          sample         24.969           ms/op
Client.listUser                       sample   3586   8.899 ± 0.130   ms/op
Client.listUser:listUser·p0.00        sample          3.715           ms/op
Client.listUser:listUser·p0.50        sample          8.520           ms/op
Client.listUser:listUser·p0.90        sample         11.867           ms/op
Client.listUser:listUser·p0.95        sample         12.763           ms/op
Client.listUser:listUser·p0.99        sample         18.129           ms/op
Client.listUser:listUser·p0.999       sample         20.102           ms/op
Client.listUser:listUser·p0.9999      sample         20.382           ms/op
Client.listUser:listUser·p1.00        sample         20.382           ms/op
