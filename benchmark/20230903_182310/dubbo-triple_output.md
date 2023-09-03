# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.124 ops/ms
# Warmup Iteration   2: 5.127 ops/ms
# Warmup Iteration   3: 8.723 ops/ms
Iteration   1: 9.216 ops/ms
Iteration   2: 9.337 ops/ms
Iteration   3: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.232 ±(99.9%) 1.780 ops/ms [Average]
  (min, avg, max) = (9.144, 9.232, 9.337), stdev = 0.098
  CI (99.9%): [7.452, 11.012] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.761 ops/ms
# Warmup Iteration   2: 8.121 ops/ms
# Warmup Iteration   3: 9.523 ops/ms
Iteration   1: 9.437 ops/ms
Iteration   2: 9.487 ops/ms
Iteration   3: 9.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.471 ±(99.9%) 0.536 ops/ms [Average]
  (min, avg, max) = (9.437, 9.471, 9.489), stdev = 0.029
  CI (99.9%): [8.935, 10.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.093 ops/ms
# Warmup Iteration   2: 7.769 ops/ms
# Warmup Iteration   3: 8.584 ops/ms
Iteration   1: 8.969 ops/ms
Iteration   2: 9.332 ops/ms
Iteration   3: 9.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.102 ±(99.9%) 3.650 ops/ms [Average]
  (min, avg, max) = (8.969, 9.102, 9.332), stdev = 0.200
  CI (99.9%): [5.452, 12.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.455 ops/ms
# Warmup Iteration   2: 7.027 ops/ms
# Warmup Iteration   3: 7.858 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 7.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.866 ±(99.9%) 1.655 ops/ms [Average]
  (min, avg, max) = (7.809, 7.866, 7.971), stdev = 0.091
  CI (99.9%): [6.211, 9.521] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.567 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.011 ms/op
Iteration   1: 3.669 ±(99.9%) 0.006 ms/op
Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
Iteration   3: 3.654 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.608 ±(99.9%) 1.694 ms/op [Average]
  (min, avg, max) = (3.501, 3.608, 3.669), stdev = 0.093
  CI (99.9%): [1.914, 5.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.933 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.567 ±(99.9%) 0.003 ms/op
Iteration   1: 3.296 ±(99.9%) 0.008 ms/op
Iteration   2: 3.256 ±(99.9%) 0.011 ms/op
Iteration   3: 3.448 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.333 ±(99.9%) 1.855 ms/op [Average]
  (min, avg, max) = (3.256, 3.333, 3.448), stdev = 0.102
  CI (99.9%): [1.479, 5.188] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.641 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.671 ±(99.9%) 0.004 ms/op
Iteration   1: 3.509 ±(99.9%) 0.006 ms/op
Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
Iteration   3: 3.377 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.495 ±(99.9%) 2.035 ms/op [Average]
  (min, avg, max) = (3.377, 3.495, 3.599), stdev = 0.112
  CI (99.9%): [1.460, 5.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.554 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.012 ms/op
Iteration   1: 4.071 ±(99.9%) 0.012 ms/op
Iteration   2: 3.999 ±(99.9%) 0.008 ms/op
Iteration   3: 4.121 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.064 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.999, 4.064, 4.121), stdev = 0.061
  CI (99.9%): [2.952, 5.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.812 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.567 ±(99.9%) 0.012 ms/op
Iteration   1: 3.658 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  21.580 ms/op
                 createUser·p0.9999: 27.396 ms/op
                 createUser·p1.00:   29.983 ms/op

Iteration   2: 3.492 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.292 ms/op
                 createUser·p0.999:  23.148 ms/op
                 createUser·p0.9999: 28.115 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 3.602 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.846 ms/op
                 createUser·p0.999:  24.447 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267770
  mean =      3.583 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5343 
    [ 2.500,  5.000) = 253698 
    [ 5.000,  7.500) = 7072 
    [ 7.500, 10.000) = 1153 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     22.557 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.286 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
Iteration   1: 3.424 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  10.912 ms/op
                 existUser·p0.9999: 21.255 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.368 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.703 ms/op
                 existUser·p0.999:  21.245 ms/op
                 existUser·p0.9999: 28.639 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 3.531 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  18.350 ms/op
                 existUser·p0.9999: 27.880 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279054
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10935 
    [ 2.500,  5.000) = 259885 
    [ 5.000,  7.500) = 6745 
    [ 7.500, 10.000) = 980 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     29.603 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.285 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.012 ms/op
Iteration   1: 3.520 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.878 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  20.811 ms/op
                 getUser·p0.9999: 23.852 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.476 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  22.807 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.512 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  20.248 ms/op
                 getUser·p0.9999: 28.075 ms/op
                 getUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273972
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3857 
    [ 2.500,  5.000) = 259595 
    [ 5.000,  7.500) = 8660 
    [ 7.500, 10.000) = 1291 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     28.521 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.386 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.016 ms/op
Iteration   1: 3.977 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  22.957 ms/op
                 listUser·p0.9999: 25.854 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   2: 4.118 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 19.927 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.104 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 17.053 ms/op
                 listUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235964
  mean =      4.065 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 222986 
    [ 5.000,  7.500) = 9962 
    [ 7.500, 10.000) = 1786 
    [10.000, 12.500) = 575 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 280 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     25.343 ms/op
     p(99.9990) =     26.900 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.232 ± 1.780  ops/ms
ClientPb.existUser                       thrpt       3   9.471 ± 0.536  ops/ms
ClientPb.getUser                         thrpt       3   9.102 ± 3.650  ops/ms
ClientPb.listUser                        thrpt       3   7.866 ± 1.655  ops/ms
ClientPb.createUser                       avgt       3   3.608 ± 1.694   ms/op
ClientPb.existUser                        avgt       3   3.333 ± 1.855   ms/op
ClientPb.getUser                          avgt       3   3.495 ± 2.035   ms/op
ClientPb.listUser                         avgt       3   4.064 ± 1.112   ms/op
ClientPb.createUser                     sample  267770   3.583 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.155           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.112           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.660           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.557           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.375           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  279054   3.440 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.538           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.144           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.812           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.951           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.884           ms/op
ClientPb.getUser                        sample  273972   3.503 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.043           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.480           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.345           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.836           ms/op
ClientPb.listUser                       sample  235964   4.065 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.276           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.104           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.126           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.343           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.099           ms/op
