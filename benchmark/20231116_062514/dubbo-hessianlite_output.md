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
# Warmup Iteration   1: 2.380 ops/ms
Iteration   1: 6.183 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.183 ops/ms


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
# Warmup Iteration   1: 6.799 ops/ms
Iteration   1: 12.534 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.534 ops/ms


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
# Warmup Iteration   1: 4.633 ops/ms
Iteration   1: 8.207 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.207 ops/ms


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
# Warmup Iteration   1: 2.262 ops/ms
Iteration   1: 3.782 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.782 ops/ms


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
# Warmup Iteration   1: 5.892 ±(99.9%) 0.074 ms/op
Iteration   1: 3.054 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.054 ms/op


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
# Warmup Iteration   1: 2.892 ±(99.9%) 0.038 ms/op
Iteration   1: 1.891 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.891 ms/op


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
# Warmup Iteration   1: 4.229 ±(99.9%) 0.044 ms/op
Iteration   1: 2.761 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.761 ms/op


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
# Warmup Iteration   1: 11.926 ±(99.9%) 0.229 ms/op
Iteration   1: 8.615 ±(99.9%) 0.104 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.615 ms/op


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.088 ms/op
Iteration   1: 3.174 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   7.458 ms/op
                 createUser·p0.999:  13.385 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10055
  mean =      3.174 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2956 
    [ 2.500,  3.750) = 4874 
    [ 3.750,  5.000) = 1957 
    [ 5.000,  6.250) = 163 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.458 ms/op
     p(99.9000) =     13.385 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 2.697 ±(99.9%) 0.046 ms/op
Iteration   1: 2.068 ±(99.9%) 0.165 ms/op
                 existUser·p0.00:   0.335 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.012 ms/op
                 existUser·p0.95:   2.167 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  137.573 ms/op
                 existUser·p0.9999: 157.382 ms/op
                 existUser·p1.00:   157.811 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15456
  mean =      2.068 ±(99.9%) 0.165 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 15371 
    [ 12.500,  25.000) = 39 
    [ 25.000,  37.500) = 6 
    [ 37.500,  50.000) = 6 
    [ 50.000,  62.500) = 2 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 1 
    [100.000, 112.500) = 3 
    [112.500, 125.000) = 6 
    [125.000, 137.500) = 7 
    [137.500, 150.000) = 7 
    [150.000, 162.500) = 8 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.335 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.012 ms/op
     p(95.0000) =      2.167 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =    137.573 ms/op
     p(99.9900) =    157.382 ms/op
     p(99.9990) =    157.811 ms/op
     p(99.9999) =    157.811 ms/op
    p(100.0000) =    157.811 ms/op


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
# Warmup Iteration   1: 5.172 ±(99.9%) 0.436 ms/op
Iteration   1: 3.165 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  10.151 ms/op
                 getUser·p0.9999: 12.887 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10287
  mean =      3.165 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 1791 
    [ 2.500,  3.750) = 6733 
    [ 3.750,  5.000) = 1570 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     10.151 ms/op
     p(99.9900) =     12.887 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


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
# Warmup Iteration   1: 13.375 ±(99.9%) 0.505 ms/op
Iteration   1: 7.454 ±(99.9%) 0.141 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   6.734 ms/op
                 listUser·p0.90:   11.321 ms/op
                 listUser·p0.95:   13.228 ms/op
                 listUser·p0.99:   17.545 ms/op
                 listUser·p0.999:  21.017 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4325
  mean =      7.454 ±(99.9%) 0.141 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 600 
    [ 5.000,  7.500) = 2149 
    [ 7.500, 10.000) = 912 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      6.734 ms/op
     p(90.0000) =     11.321 ms/op
     p(95.0000) =     13.228 ms/op
     p(99.0000) =     17.545 ms/op
     p(99.9000) =     21.017 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           6.183          ops/ms
Client.existUser                       thrpt          12.534          ops/ms
Client.getUser                         thrpt           8.207          ops/ms
Client.listUser                        thrpt           3.782          ops/ms
Client.createUser                       avgt           3.054           ms/op
Client.existUser                        avgt           1.891           ms/op
Client.getUser                          avgt           2.761           ms/op
Client.listUser                         avgt           8.615           ms/op
Client.createUser                     sample  10055    3.174 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample           1.284           ms/op
Client.createUser:createUser·p0.50    sample           2.904           ms/op
Client.createUser:createUser·p0.90    sample           4.252           ms/op
Client.createUser:createUser·p0.95    sample           4.522           ms/op
Client.createUser:createUser·p0.99    sample           7.458           ms/op
Client.createUser:createUser·p0.999   sample          13.385           ms/op
Client.createUser:createUser·p0.9999  sample          13.730           ms/op
Client.createUser:createUser·p1.00    sample          13.730           ms/op
Client.existUser                      sample  15456    2.068 ± 0.165   ms/op
Client.existUser:existUser·p0.00      sample           0.335           ms/op
Client.existUser:existUser·p0.50      sample           1.673           ms/op
Client.existUser:existUser·p0.90      sample           2.012           ms/op
Client.existUser:existUser·p0.95      sample           2.167           ms/op
Client.existUser:existUser·p0.99      sample           4.735           ms/op
Client.existUser:existUser·p0.999     sample         137.573           ms/op
Client.existUser:existUser·p0.9999    sample         157.382           ms/op
Client.existUser:existUser·p1.00      sample         157.811           ms/op
Client.getUser                        sample  10287    3.165 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample           0.698           ms/op
Client.getUser:getUser·p0.50          sample           3.117           ms/op
Client.getUser:getUser·p0.90          sample           3.949           ms/op
Client.getUser:getUser·p0.95          sample           4.293           ms/op
Client.getUser:getUser·p0.99          sample           6.193           ms/op
Client.getUser:getUser·p0.999         sample          10.151           ms/op
Client.getUser:getUser·p0.9999        sample          12.887           ms/op
Client.getUser:getUser·p1.00          sample          12.911           ms/op
Client.listUser                       sample   4325    7.454 ± 0.141   ms/op
Client.listUser:listUser·p0.00        sample           1.575           ms/op
Client.listUser:listUser·p0.50        sample           6.734           ms/op
Client.listUser:listUser·p0.90        sample          11.321           ms/op
Client.listUser:listUser·p0.95        sample          13.228           ms/op
Client.listUser:listUser·p0.99        sample          17.545           ms/op
Client.listUser:listUser·p0.999       sample          21.017           ms/op
Client.listUser:listUser·p0.9999      sample          22.675           ms/op
Client.listUser:listUser·p1.00        sample          22.675           ms/op
