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
# Warmup Iteration   1: 2.366 ops/ms
Iteration   1: 5.681 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.681 ops/ms


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
# Warmup Iteration   1: 6.712 ops/ms
Iteration   1: 13.585 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.585 ops/ms


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
# Warmup Iteration   1: 4.811 ops/ms
Iteration   1: 9.977 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.977 ops/ms


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
# Warmup Iteration   1: 2.474 ops/ms
Iteration   1: 4.210 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.210 ops/ms


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.070 ms/op
Iteration   1: 3.074 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.074 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.032 ms/op
Iteration   1: 1.839 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.839 ms/op


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.051 ms/op
Iteration   1: 3.254 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.254 ms/op


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
# Warmup Iteration   1: 13.420 ±(99.9%) 0.229 ms/op
Iteration   1: 8.068 ±(99.9%) 0.112 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.068 ms/op


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
# Warmup Iteration   1: 4.792 ±(99.9%) 0.087 ms/op
Iteration   1: 3.003 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   10.068 ms/op
                 createUser·p0.999:  26.608 ms/op
                 createUser·p0.9999: 27.456 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10650
  mean =      3.003 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4217 
    [ 2.500,  5.000) = 6161 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =     10.068 ms/op
     p(99.9000) =     26.608 ms/op
     p(99.9900) =     27.456 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 3.069 ±(99.9%) 0.063 ms/op
Iteration   1: 1.716 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.493 ms/op
                 existUser·p0.50:   1.677 ms/op
                 existUser·p0.90:   2.013 ms/op
                 existUser·p0.95:   2.187 ms/op
                 existUser·p0.99:   3.013 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 10.853 ms/op
                 existUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18646
  mean =      1.716 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 808 
    [ 1.250,  2.500) = 17480 
    [ 2.500,  3.750) = 250 
    [ 3.750,  5.000) = 1 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      1.677 ms/op
     p(90.0000) =      2.013 ms/op
     p(95.0000) =      2.187 ms/op
     p(99.0000) =      3.013 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     10.853 ms/op
     p(99.9990) =     10.895 ms/op
     p(99.9999) =     10.895 ms/op
    p(100.0000) =     10.895 ms/op


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.091 ms/op
Iteration   1: 3.182 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.158 ms/op
                 getUser·p0.99:   5.323 ms/op
                 getUser·p0.999:  13.598 ms/op
                 getUser·p0.9999: 14.336 ms/op
                 getUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10018
  mean =      3.182 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1294 
    [ 2.500,  3.750) = 7584 
    [ 3.750,  5.000) = 995 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.158 ms/op
     p(99.0000) =      5.323 ms/op
     p(99.9000) =     13.598 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 12.285 ±(99.9%) 0.430 ms/op
Iteration   1: 8.669 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   8.249 ms/op
                 listUser·p0.90:   11.420 ms/op
                 listUser·p0.95:   12.517 ms/op
                 listUser·p0.99:   17.077 ms/op
                 listUser·p0.999:  19.034 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3685
  mean =      8.669 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 87 
    [ 5.000,  7.500) = 1099 
    [ 7.500, 10.000) = 1609 
    [10.000, 12.500) = 698 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      8.249 ms/op
     p(90.0000) =     11.420 ms/op
     p(95.0000) =     12.517 ms/op
     p(99.0000) =     17.077 ms/op
     p(99.9000) =     19.034 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.681          ops/ms
Client.existUser                       thrpt         13.585          ops/ms
Client.getUser                         thrpt          9.977          ops/ms
Client.listUser                        thrpt          4.210          ops/ms
Client.createUser                       avgt          3.074           ms/op
Client.existUser                        avgt          1.839           ms/op
Client.getUser                          avgt          3.254           ms/op
Client.listUser                         avgt          8.068           ms/op
Client.createUser                     sample  10650   3.003 ± 0.057   ms/op
Client.createUser:createUser·p0.00    sample          0.989           ms/op
Client.createUser:createUser·p0.50    sample          2.666           ms/op
Client.createUser:createUser·p0.90    sample          3.777           ms/op
Client.createUser:createUser·p0.95    sample          4.194           ms/op
Client.createUser:createUser·p0.99    sample         10.068           ms/op
Client.createUser:createUser·p0.999   sample         26.608           ms/op
Client.createUser:createUser·p0.9999  sample         27.456           ms/op
Client.createUser:createUser·p1.00    sample         27.492           ms/op
Client.existUser                      sample  18646   1.716 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.493           ms/op
Client.existUser:existUser·p0.50      sample          1.677           ms/op
Client.existUser:existUser·p0.90      sample          2.013           ms/op
Client.existUser:existUser·p0.95      sample          2.187           ms/op
Client.existUser:existUser·p0.99      sample          3.013           ms/op
Client.existUser:existUser·p0.999     sample         10.715           ms/op
Client.existUser:existUser·p0.9999    sample         10.853           ms/op
Client.existUser:existUser·p1.00      sample         10.895           ms/op
Client.getUser                        sample  10018   3.182 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          1.067           ms/op
Client.getUser:getUser·p0.50          sample          3.138           ms/op
Client.getUser:getUser·p0.90          sample          3.793           ms/op
Client.getUser:getUser·p0.95          sample          4.158           ms/op
Client.getUser:getUser·p0.99          sample          5.323           ms/op
Client.getUser:getUser·p0.999         sample         13.598           ms/op
Client.getUser:getUser·p0.9999        sample         14.336           ms/op
Client.getUser:getUser·p1.00          sample         14.336           ms/op
Client.listUser                       sample   3685   8.669 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          1.872           ms/op
Client.listUser:listUser·p0.50        sample          8.249           ms/op
Client.listUser:listUser·p0.90        sample         11.420           ms/op
Client.listUser:listUser·p0.95        sample         12.517           ms/op
Client.listUser:listUser·p0.99        sample         17.077           ms/op
Client.listUser:listUser·p0.999       sample         19.034           ms/op
Client.listUser:listUser·p0.9999      sample         20.546           ms/op
Client.listUser:listUser·p1.00        sample         20.546           ms/op
