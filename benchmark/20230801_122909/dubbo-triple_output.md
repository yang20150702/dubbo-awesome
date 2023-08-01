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
# Warmup Iteration   1: 2.356 ops/ms
# Warmup Iteration   2: 5.476 ops/ms
# Warmup Iteration   3: 9.085 ops/ms
Iteration   1: 9.485 ops/ms
Iteration   2: 9.878 ops/ms
Iteration   3: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.752 ±(99.9%) 4.215 ops/ms [Average]
  (min, avg, max) = (9.485, 9.752, 9.891), stdev = 0.231
  CI (99.9%): [5.536, 13.967] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.312 ops/ms
# Warmup Iteration   2: 9.337 ops/ms
# Warmup Iteration   3: 10.182 ops/ms
Iteration   1: 10.243 ops/ms
Iteration   2: 9.898 ops/ms
Iteration   3: 9.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.036 ±(99.9%) 3.329 ops/ms [Average]
  (min, avg, max) = (9.898, 10.036, 10.243), stdev = 0.182
  CI (99.9%): [6.708, 13.365] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 8.155 ops/ms
# Warmup Iteration   3: 9.278 ops/ms
Iteration   1: 9.480 ops/ms
Iteration   2: 9.542 ops/ms
Iteration   3: 9.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.402 ±(99.9%) 3.512 ops/ms [Average]
  (min, avg, max) = (9.182, 9.402, 9.542), stdev = 0.193
  CI (99.9%): [5.889, 12.914] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.764 ops/ms
# Warmup Iteration   2: 7.047 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 8.014 ops/ms
Iteration   3: 8.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.013 ±(99.9%) 0.507 ops/ms [Average]
  (min, avg, max) = (7.985, 8.013, 8.041), stdev = 0.028
  CI (99.9%): [7.506, 8.520] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.627 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.004 ms/op
Iteration   1: 3.296 ±(99.9%) 0.005 ms/op
Iteration   2: 3.318 ±(99.9%) 0.006 ms/op
Iteration   3: 3.463 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.359 ±(99.9%) 1.653 ms/op [Average]
  (min, avg, max) = (3.296, 3.359, 3.463), stdev = 0.091
  CI (99.9%): [1.706, 5.012] (assumes normal distribution)


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
# Warmup Iteration   1: 9.166 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.004 ms/op
Iteration   1: 3.131 ±(99.9%) 0.001 ms/op
Iteration   2: 3.170 ±(99.9%) 0.010 ms/op
Iteration   3: 3.292 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.198 ±(99.9%) 1.535 ms/op [Average]
  (min, avg, max) = (3.131, 3.198, 3.292), stdev = 0.084
  CI (99.9%): [1.662, 4.733] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.495 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.003 ms/op
Iteration   1: 3.269 ±(99.9%) 0.003 ms/op
Iteration   2: 3.256 ±(99.9%) 0.006 ms/op
Iteration   3: 3.262 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.262 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (3.256, 3.262, 3.269), stdev = 0.007
  CI (99.9%): [3.142, 3.382] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.297 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.005 ms/op
Iteration   1: 3.730 ±(99.9%) 0.013 ms/op
Iteration   2: 3.756 ±(99.9%) 0.008 ms/op
Iteration   3: 3.725 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.737 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.725, 3.737, 3.756), stdev = 0.017
  CI (99.9%): [3.428, 4.046] (assumes normal distribution)


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
# Warmup Iteration   1: 9.209 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.278 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  12.108 ms/op
                 createUser·p0.9999: 22.429 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.355 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 24.286 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   3: 3.269 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  12.742 ms/op
                 createUser·p0.9999: 16.712 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294575
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24864 
    [ 2.500,  5.000) = 265077 
    [ 5.000,  7.500) = 3623 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.454 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.568 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.009 ms/op
Iteration   1: 3.171 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  11.245 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.165 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  9.025 ms/op
                 existUser·p0.9999: 23.884 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  16.544 ms/op
                 existUser·p0.9999: 22.542 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302580
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21987 
    [ 2.500,  5.000) = 276010 
    [ 5.000,  7.500) = 3817 
    [ 7.500, 10.000) = 401 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     13.589 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 8.759 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
Iteration   1: 3.397 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 26.430 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  8.952 ms/op
                 getUser·p0.9999: 27.034 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  10.174 ms/op
                 getUser·p0.9999: 21.202 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294524
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17796 
    [ 2.500,  5.000) = 270293 
    [ 5.000,  7.500) = 5683 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     15.800 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.503 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 10.577 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.012 ms/op
Iteration   1: 3.764 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.433 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 22.840 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 3.770 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 16.433 ms/op
                 listUser·p1.00:   16.482 ms/op

Iteration   3: 3.773 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254640
  mean =      3.769 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 246670 
    [ 5.000,  7.500) = 5794 
    [ 7.500, 10.000) = 1286 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 327 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.091 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     24.194 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.752 ± 4.215  ops/ms
ClientPb.existUser                       thrpt       3  10.036 ± 3.329  ops/ms
ClientPb.getUser                         thrpt       3   9.402 ± 3.512  ops/ms
ClientPb.listUser                        thrpt       3   8.013 ± 0.507  ops/ms
ClientPb.createUser                       avgt       3   3.359 ± 1.653   ms/op
ClientPb.existUser                        avgt       3   3.198 ± 1.535   ms/op
ClientPb.getUser                          avgt       3   3.262 ± 0.120   ms/op
ClientPb.listUser                         avgt       3   3.737 ± 0.309   ms/op
ClientPb.createUser                     sample  294575   3.255 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.565           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.364           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.740           ms/op
ClientPb.existUser                      sample  302580   3.171 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.909           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.589           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.675           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.183           ms/op
ClientPb.getUser                        sample  294524   3.258 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.831           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.800           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.378           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.246           ms/op
ClientPb.listUser                       sample  254640   3.769 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.433           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.091           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.053           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.642           ms/op
